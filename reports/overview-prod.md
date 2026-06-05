# Overview: prod
*Last updated: 2026-06-05 15:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T15:25 (1428 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,506 | avg: 12,122 | max: 84,644 | trend: decreasing (-0.96/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 163.7MB | avg: 185.4MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▄▄▅▆▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,506 | 15,495 | -989 | 12,122 | 84,644 | decreasing (-0.96/hr) |
| Heap InUse | 163.7MB | 233.0MB | -69.3MB | 185.4MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1056.1MB | 1055.2MB | +0.9MB | 2650.5MB | 6883.9MB | |
| Heap Objects | 696,509 | 1,323,274 | -626765 | 823,635 | 17,165,538 | |

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
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 186 | 16,404 | 259.6MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.14MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 6.16GB |
| 2 | `jackskj/carta.getUniqueId` | 5.84GB |
| 3 | `segmentio/kafka-go.makePartitions` | 5.46GB |
| 4 | `reflect.unsafe_New` | 5.01GB |
| 5 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.46GB |
| 6 | `fmt.Sprintf` | 4.37GB |
| 7 | `fmt.(*buffer).writeString` | 3.92GB |
| 8 | `carta/value.NewCell` | 3.61GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 2.94GB |
| 10 | `reflect.unsafe_NewArray` | 2.85GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 395.71MB | 380.97MB | 185.89MB | 0B |
| `evaluation.mergeMetadata` | 204.55MB | 197.05MB | 93.01MB | 0B |
| `local.(*Client).EvaluateV2` | 628.00MB | 610.66MB | 297.33MB | 0B |
| `local.topologicalSort` | 95.60MB | 94.08MB | 45.30MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 594.07MB | 577.25MB | 284.11MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 87.31MB | 86.27MB | 40.20MB | 0B |
| `localEvaluation.getMapOfValue` | 594.07MB | 577.25MB | 284.11MB | 0B |
| `utils.ParseFeatureFlag` | 595.57MB | 578.75MB | 284.50MB | 0B |

**Total FF alloc (current snapshot):** 3.12GB  |  **24h avg:** 1.48GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 98.34MB | 32/1428 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.97MB | 52/1428 | `███████████░░░░ 78%` |
| 3 | `database/sql.convertAssignRows` | 40.41MB | 65/1428 | `██████░░░░░░░░░ 41%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1079/1428 | `█████░░░░░░░░░░ 37%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1428 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.75MB | 1079/1428 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.19MB | 838/1428 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1428 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.06MB | 24/1428 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1428 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1428 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1428 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1428 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1428 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1428 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 32.27GB | 1050/1428 | `███░░░░░░░░░░░░ 25%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1428 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1428 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1428 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.98GB | 612/1428 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
