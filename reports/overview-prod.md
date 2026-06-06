# Overview: prod
*Last updated: 2026-06-06 23:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T23:40 (1814 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,084 | avg: 12,879 | max: 84,644 | trend: INCREASING (+3.42/hr))
```
▂▁▁▁▅▁▂▁▁▃▂▅▁▁▃▂▆▂▂▆▃▅▄▂▃▃▁▁▇▄▄█▂▁▂▂▂▂▂▂▇▃▁▂▅▃▄▁▁▁▂▃▅▂▁▁▆▁▂▁▂▂▂▃▄▁▂▄▃▂▃▂▃▁▁▁▃▁▅▁▁▁▁▁▁▁▁▁▃▁▄▁▁▁▁▁
```

**Heap InUse** (current: 137.1MB | avg: 192.1MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▄▃▁▄▃▃▄▂▂▆▁▃▇▆█▄▂▂▁▂▂▅▃▁▄▄▂▅▅▅▄▃▄▄▄▅▃▂▂▄▅▄▅▁▅▄▇▆▄▄▄▃▆▂▆▁▄▁▂▃▇▂▂▅▅▄▁▄▆▁▆▁▄▃▁▃▇▆▆▄▂▆▃▆▄▁▅▁▇▄▅▄▂▅▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,084 | 14,163 | -79 | 12,879 | 84,644 | INCREASING (+3.42/hr) |
| Heap InUse | 137.1MB | 166.9MB | -29.8MB | 192.1MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 853.7MB | 853.6MB | +0.1MB | 2323.5MB | 6883.9MB | |
| Heap Objects | 825,987 | 1,189,177 | -363190 | 861,337 | 17,165,538 | |

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
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 285 | 15,860 | 222.4MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_New` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 14.27GB |
| 2 | `reflect.unsafe_NewArray` | 7.25GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.12GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.01GB |
| 5 | `reflect.MakeSlice` | 4.08GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.58GB |
| 7 | `reflect.growslice` | 2.19GB |
| 8 | `fmt.Sprintf` | 2.07GB |
| 9 | `jackskj/carta.getUniqueId` | 2.0GB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.81GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 413.47MB | 410.97MB | 367.48MB | 0B |
| `evaluation.mergeMetadata` | 217.05MB | 214.55MB | 191.35MB | 0B |
| `local.(*Client).EvaluateV2` | 623.10MB | 619.55MB | 551.35MB | 0B |
| `local.topologicalSort` | 83.51MB | 83.51MB | 73.69MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 623.68MB | 620.13MB | 548.96MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 60.28MB | 60.28MB | 55.39MB | 0B |
| `localEvaluation.getMapOfValue` | 623.68MB | 620.13MB | 548.96MB | 0B |
| `utils.ParseFeatureFlag` | 625.18MB | 621.63MB | 550.10MB | 0B |

**Total FF alloc (current snapshot):** 3.19GB  |  **24h avg:** 2.82GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1814 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1814 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1465/1814 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 35.4MB | 76/1814 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1814 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.99MB | 1465/1814 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.91MB | 1107/1814 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1814 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1814 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1814 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1814 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1814 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1814 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1814 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1814 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1814 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 28.05GB | 1228/1814 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1814 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1814 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1814 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
