# Overview: prod
*Last updated: 2026-06-07 23:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T23:05 (2095 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,318 | avg: 13,223 | max: 84,644 | trend: INCREASING (+3.92/hr))
```
▅▃▂▃▂▂▃▂▆█▄▆▁▁▁▁▃▂▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▂▂▂▁▂▁▂▄▂▂▂▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 201.5MB | avg: 197.5MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▃▆▂█▅▅▄▂▅▅▆▄▁▃▂▅▅▃▄▁▅▂▅▁▁▃▃▃▄▁▂▃▃▃▄▂▁▃▁▂▁▂▃▃▃▁▁▄▅▄▁▅▂▁▅▄▂▂▁▁▄▄▁▄▂▂▂▂▂▃▄▆▅▂▃▅▂▅▂▂▂▂▃▄▄▃▃▃▄▄▄▄▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,318 | 14,084 | +234 | 13,223 | 84,644 | INCREASING (+3.92/hr) |
| Heap InUse | 201.5MB | 209.9MB | -8.4MB | 197.5MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3221.2MB | 3221.2MB | +0.0MB | 2298.4MB | 6883.9MB | |
| Heap Objects | 685,127 | 1,027,857 | -342730 | 890,460 | 17,165,538 | |

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
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 278 | 15,463 | 233.5MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 46.17GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.04GB |
| 3 | `reflect.growslice` | 34.44GB |
| 4 | `jackskj/carta.getUniqueId` | 29.58GB |
| 5 | `reflect.unsafe_New` | 26.6GB |
| 6 | `reflect.unsafe_NewArray` | 23.62GB |
| 7 | `fmt.(*buffer).writeString` | 21.36GB |
| 8 | `carta/value.NewCell` | 19.01GB |
| 9 | `fmt.Sprintf` | 16.99GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 16.3GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.27GB | 1.26GB | 1.20GB | 0B |
| `evaluation.mergeMetadata` | 667.16MB | 664.16MB | 636.10MB | 0B |
| `local.(*Client).EvaluateV2` | 1.92GB | 1.91GB | 1.82GB | 0B |
| `local.topologicalSort` | 256.63MB | 256.12MB | 246.13MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.90GB | 1.90GB | 1.82GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 209.53MB | 209.53MB | 195.10MB | 0B |
| `localEvaluation.getMapOfValue` | 1.90GB | 1.90GB | 1.82GB | 0B |
| `utils.ParseFeatureFlag` | 1.91GB | 1.90GB | 1.82GB | 0B |

**Total FF alloc (current snapshot):** 10.01GB  |  **24h avg:** 9.53GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2095 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2095 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1746/2095 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 33.01MB | 82/2095 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 19.49MB | 1746/2095 | `███░░░░░░░░░░░░ 22%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2095 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.83MB | 1273/2095 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2095 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2095 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2095 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2095 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2095 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2095 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2095 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2095 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2095 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2095 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.48GB | 612/2095 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `segmentio/kafka-go.makePartitions` | 14.62GB | 1469/2095 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2095 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
