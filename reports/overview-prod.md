# Overview: prod
*Last updated: 2026-06-06 19:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T19:00 (1758 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,187 | avg: 12,836 | max: 84,644 | trend: INCREASING (+3.45/hr))
```
▅▃▂▃▁▁▁▁▁▁▁▁▁▂▂▄▂▄▅▄▁▅▄▂▃▃▂▂▁▁▁▁▁▁▁▃▅▄▃▄▄▂█▂▁▅▂▁▂▂▃▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▂▁▁▃▁▂▂▁▁▁▁▁▃▂▂▃▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 149.5MB | avg: 193.5MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▅▅▅▄▄▅▃▅▄▄▃▂▅▃▅▅▄▄▄▄▃▅▄▅▃▆▁▂▁█▁▂▁▁▁▁▂▂▃▄▂▃▃▂▂▃▂▂▁▃▂▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▁▁▁▁▁▁▂▁▁▂▁▁▂▂▂▁▁▂▁▁▂▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,187 | 14,243 | -56 | 12,836 | 84,644 | INCREASING (+3.45/hr) |
| Heap InUse | 149.5MB | 125.8MB | +23.7MB | 193.5MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 852.8MB | 852.7MB | +0.1MB | 2370.3MB | 6883.9MB | |
| Heap Objects | 875,256 | 498,931 | +376325 | 861,063 | 17,165,538 | |

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
| 2026-06-06 | 229 | 16,263 | 240.3MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.89GB |
| 2 | `reflect.unsafe_NewArray` | 3.97GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.37GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 3.0GB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 2.75GB |
| 6 | `reflect.MakeSlice` | 2.25GB |
| 7 | `reflect.growslice` | 1.96GB |
| 8 | `jackskj/carta.getUniqueId` | 1.85GB |
| 9 | `reflect.unsafe_New` | 1.58GB |
| 10 | `fmt.Sprintf` | 1.51GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 288.18MB | 284.62MB | 201.70MB | 0B |
| `evaluation.mergeMetadata` | 150.04MB | 148.54MB | 103.09MB | 0B |
| `local.(*Client).EvaluateV2` | 427.45MB | 422.30MB | 299.86MB | 0B |
| `local.topologicalSort` | 55.67MB | 55.16MB | 39.85MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 421.75MB | 417.15MB | 297.27MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 45.01MB | 44.47MB | 29.46MB | 0B |
| `localEvaluation.getMapOfValue` | 421.75MB | 417.15MB | 297.27MB | 0B |
| `utils.ParseFeatureFlag` | 422.26MB | 417.65MB | 297.33MB | 0B |

**Total FF alloc (current snapshot):** 2.18GB  |  **24h avg:** 1.53GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1758 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 68.14MB | 60/1758 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1409/1758 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 36.28MB | 74/1758 | `██████░░░░░░░░░ 41%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1758 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.21MB | 1409/1758 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.18MB | 1083/1758 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1758 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1758 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1758 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1758 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1758 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1758 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1758 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1758 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 29.24GB | 1172/1758 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1758 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1758 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1758 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.62GB | 887/1758 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
