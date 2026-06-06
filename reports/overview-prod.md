# Overview: prod
*Last updated: 2026-06-06 19:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T19:40 (1766 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,114 | avg: 12,843 | max: 84,644 | trend: INCREASING (+3.45/hr))
```
▁▁▁▁▁▂▂▄▂▄▅▄▁▅▄▂▃▃▂▂▁▁▁▁▁▁▁▃▅▄▃▄▄▂█▂▁▅▂▁▂▂▃▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▂▁▁▃▁▂▂▁▁▁▁▁▃▂▂▃▁▁▁▁▁▁▁▁▃▂▁▁▂▁▂▁
```

**Heap InUse** (current: 176.9MB | avg: 193.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▄▄▃▂▅▃▅▅▄▄▄▄▃▅▄▅▃▆▁▂▁█▁▂▁▁▁▁▂▂▃▄▂▃▃▂▂▃▂▂▁▃▂▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▁▁▁▁▁▁▂▁▁▂▁▁▂▂▂▁▁▂▁▁▂▁▁▁▂▂▂▂▁▂▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,114 | 14,430 | -316 | 12,843 | 84,644 | INCREASING (+3.45/hr) |
| Heap InUse | 176.9MB | 192.0MB | -15.1MB | 193.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 853.2MB | 852.8MB | +0.4MB | 2363.5MB | 6883.9MB | |
| Heap Objects | 1,300,127 | 1,191,241 | +108886 | 861,273 | 17,165,538 | |

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
| 2026-06-06 | 237 | 16,197 | 237.6MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.79GB |
| 2 | `reflect.unsafe_NewArray` | 4.46GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.93GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 3.23GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.09GB |
| 6 | `reflect.MakeSlice` | 2.53GB |
| 7 | `reflect.growslice` | 2.0GB |
| 8 | `jackskj/carta.getUniqueId` | 1.88GB |
| 9 | `fmt.Sprintf` | 1.63GB |
| 10 | `reflect.unsafe_New` | 1.62GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 314.05MB | 311.02MB | 231.04MB | 0B |
| `evaluation.mergeMetadata` | 162.54MB | 161.54MB | 119.25MB | 0B |
| `local.(*Client).EvaluateV2` | 469.90MB | 463.74MB | 343.33MB | 0B |
| `local.topologicalSort` | 61.24MB | 60.23MB | 45.41MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 463.22MB | 456.56MB | 339.39MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 50.07MB | 50.07MB | 34.68MB | 0B |
| `localEvaluation.getMapOfValue` | 463.22MB | 456.56MB | 339.39MB | 0B |
| `utils.ParseFeatureFlag` | 464.22MB | 457.56MB | 339.62MB | 0B |

**Total FF alloc (current snapshot):** 2.39GB  |  **24h avg:** 1.75GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1766 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 68.14MB | 60/1766 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1417/1766 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 35.84MB | 75/1766 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1766 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.18MB | 1417/1766 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.09MB | 1090/1766 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1766 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1766 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1766 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1766 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1766 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1766 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1766 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1766 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 29.06GB | 1180/1766 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1766 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1766 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1766 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.52GB | 895/1766 | `█░░░░░░░░░░░░░░ 10%` |

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
