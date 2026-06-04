# Overview: prod
*Last updated: 2026-06-04 23:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T23:25 (1236 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,337 | avg: 11,464 | max: 84,644 | trend: decreasing (-9.01/hr))
```
▄▅▂▂▁▂▃▂▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▁▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄
```

**Heap InUse** (current: 327.2MB | avg: 174.2MB | max: 2823.8MB | trend: stable (-0.10MB/hr))
```
▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁▂▃▄▄▃▄▂▁▁▂▁▂▂▁▁▂▁▁█▁▁▁▁▁▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,337 | 15,450 | +2887 | 11,464 | 84,644 | decreasing (-9.01/hr) |
| Heap InUse | 327.2MB | 208.7MB | +118.5MB | 174.2MB | 2823.8MB | stable (-0.10MB/hr) |
| Heap Sys | 792.5MB | 810.2MB | -17.7MB | 2660.3MB | 6883.9MB | |
| Heap Objects | 1,427,952 | 1,074,966 | +352986 | 756,031 | 14,090,816 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 282 | 16,591 | 267.2MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 32.68MB |
| 3 | `bufio.NewReaderSize` | 15.07MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.06MB |
| 5 | `runtime.mallocgc` | 11.01MB |
| 6 | `bufio.NewWriterSize` | 9.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 9 | `crypto/tls.Client` | 4.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.9GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 761.97MB |
| 3 | `segmentio/kafka-go.makePartitions` | 613.17MB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 513.83MB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 428.38MB |
| 6 | `fmt.Sprintf` | 417.12MB |
| 7 | `reflect.unsafe_NewArray` | 339.93MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 335.01MB |
| 9 | `database/sql.convertAssignRows` | 272.01MB |
| 10 | `jackskj/carta.getUniqueId` | 215.04MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 50.30MB | 41.11MB | 418.11MB | 0B |
| `evaluation.mergeMetadata` | 27.51MB | 23.01MB | 214.86MB | 0B |
| `local.(*Client).EvaluateV2` | 68.92MB | 57.10MB | 653.83MB | 0B |
| `local.topologicalSort` | 9.06MB | 8.56MB | 89.97MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 59.68MB | 49.93MB | 576.70MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 12.82MB | 10.22MB | 135.47MB | 0B |
| `localEvaluation.getMapOfValue` | 59.68MB | 49.93MB | 576.70MB | 0B |
| `utils.ParseFeatureFlag` | 59.68MB | 49.93MB | 576.94MB | 0B |

**Total FF alloc (current snapshot):** 347.64MB  |  **24h avg:** 3.17GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.38MB | 41/1236 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.62MB | 25/1236 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 887/1236 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.49MB | 53/1236 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.18MB | 887/1236 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1236 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.2MB | 671/1236 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1236 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1236 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1236 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1236 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1236 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1236 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1236 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1236 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.49GB | 859/1236 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1236 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.82GB | 782/1236 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.0GB | 474/1236 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.07GB | 620/1236 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 439.8MB at 2026-05-19T17:02 (2.5x avg)
