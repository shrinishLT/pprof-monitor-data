# Overview: prod
*Last updated: 2026-06-04 19:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T19:25 (1188 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,359 | avg: 11,279 | max: 84,644 | trend: decreasing (-12.08/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▇▇▇▄▂▃▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 207.5MB | avg: 171.1MB | max: 2823.8MB | trend: stable (-0.15MB/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▃▃▅▅▅▄▅▃▃▃▂▃▃▄▄▂▂▂▂▃▃▃▂▂█▂▄▄▃▄▄▅▄▃▂▃▄▂▂▂▂▃▃▂▁▃▃▃▃▅▄▄▁▂▃▂▂▂▁▁▂▁▂▂▂▁▁▁▂▂▂▁▁▂▂▁▁▂▂▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,359 | 14,255 | +104 | 11,279 | 84,644 | decreasing (-12.08/hr) |
| Heap InUse | 207.5MB | 167.6MB | +39.9MB | 171.1MB | 2823.8MB | stable (-0.15MB/hr) |
| Heap Sys | 3860.8MB | 3860.8MB | +0.0MB | 2630.2MB | 6883.9MB | |
| Heap Objects | 1,197,938 | 903,678 | +294260 | 740,060 | 14,090,816 | |

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
| 2026-06-04 | 234 | 16,703 | 270.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 5.57MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.52MB |
| 7 | `reflect.mapassign_faststr0` | 3.5MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewReaderSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 9.07GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.8GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.6GB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.25GB |
| 5 | `database/sql.convertAssignRows` | 2.47GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.32GB |
| 7 | `fmt.Sprintf` | 2.31GB |
| 8 | `reflect.unsafe_NewArray` | 1.68GB |
| 9 | `jackskj/carta.getUniqueId` | 1.63GB |
| 10 | `reflect.growslice` | 1.22GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 297.13MB | 288.52MB | 310.30MB | 0B |
| `evaluation.mergeMetadata` | 154.04MB | 150.04MB | 161.81MB | 0B |
| `local.(*Client).EvaluateV2` | 463.82MB | 452.09MB | 481.11MB | 0B |
| `local.topologicalSort` | 68.32MB | 66.79MB | 69.59MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 412.86MB | 401.58MB | 442.23MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 95.54MB | 93.54MB | 82.35MB | 0B |
| `localEvaluation.getMapOfValue` | 412.86MB | 401.58MB | 442.23MB | 0B |
| `utils.ParseFeatureFlag` | 412.86MB | 401.58MB | 442.23MB | 0B |

**Total FF alloc (current snapshot):** 2.26GB  |  **24h avg:** 2.37GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1188 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1188 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 839/1188 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1188 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.65MB | 839/1188 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1188 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.26MB | 625/1188 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1188 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1188 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1188 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1188 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1188 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1188 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1188 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1188 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.06GB | 811/1188 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1188 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.64GB | 734/1188 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 11.58GB | 430/1188 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.51GB | 572/1188 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
