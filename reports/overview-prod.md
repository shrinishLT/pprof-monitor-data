# Overview: prod
*Last updated: 2026-06-04 21:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T21:21 (1211 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,651 | avg: 11,367 | max: 84,644 | trend: decreasing (-10.55/hr))
```
▁▄▅▅▄▁▁▂▃▄▃▃▂▁▂▃▅▆▄▅▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▅▄▄▅█▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▄▄▅▄▂▂▃▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 169.7MB | avg: 172.4MB | max: 2823.8MB | trend: stable (-0.12MB/hr))
```
▁▂▃▃▄▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,651 | 14,326 | +325 | 11,367 | 84,644 | decreasing (-10.55/hr) |
| Heap InUse | 169.7MB | 199.0MB | -29.3MB | 172.4MB | 2823.8MB | stable (-0.12MB/hr) |
| Heap Sys | 3854.0MB | 3854.5MB | -0.5MB | 2653.4MB | 6883.9MB | |
| Heap Objects | 892,031 | 1,218,677 | -326646 | 746,724 | 14,090,816 | |

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
| 2026-06-04 | 257 | 16,634 | 268.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `reflect.growslice` | 5.37MB |
| 6 | `bytes.growSlice` | 4.52MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 8 | `bufio.NewReaderSize` | 2.54MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.08GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.69GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.98GB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.89GB |
| 5 | `fmt.Sprintf` | 5.84GB |
| 6 | `database/sql.convertAssignRows` | 4.27GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.13GB |
| 8 | `jackskj/carta.getUniqueId` | 3.45GB |
| 9 | `reflect.unsafe_NewArray` | 3.03GB |
| 10 | `strconv.appendQuotedWith` | 2.9GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 512.06MB | 496.86MB | 289.95MB | 0B |
| `evaluation.mergeMetadata` | 261.56MB | 252.06MB | 150.13MB | 0B |
| `local.(*Client).EvaluateV2` | 808.79MB | 785.74MB | 453.74MB | 0B |
| `local.topologicalSort` | 109.78MB | 107.25MB | 64.91MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 710.48MB | 693.60MB | 403.89MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 169.60MB | 161.90MB | 92.38MB | 0B |
| `localEvaluation.getMapOfValue` | 710.48MB | 693.60MB | 403.89MB | 0B |
| `utils.ParseFeatureFlag` | 710.98MB | 694.10MB | 403.94MB | 0B |

**Total FF alloc (current snapshot):** 3.90GB  |  **24h avg:** 2.21GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1211 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1211 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 862/1211 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1211 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.43MB | 862/1211 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1211 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.19MB | 648/1211 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1211 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1211 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1211 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1211 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1211 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1211 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1211 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1211 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.27GB | 834/1211 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1211 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.23GB | 757/1211 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.21GB | 453/1211 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.28GB | 595/1211 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
