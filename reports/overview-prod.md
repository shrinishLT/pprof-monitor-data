# Overview: prod
*Last updated: 2026-06-06 19:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T19:45 (1767 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,077 | avg: 12,844 | max: 84,644 | trend: INCREASING (+3.45/hr))
```
▁▁▁▁▂▂▄▂▄▅▄▁▅▄▂▃▃▂▂▁▁▁▁▁▁▁▃▅▄▃▄▄▂█▂▁▅▂▁▂▂▃▁▁▂▁▁▁▁▁▁▂▁▁▁▁▂▁▂▁▁▁▁▂▁▁▃▁▂▂▁▁▁▁▁▃▂▂▃▁▁▁▁▁▁▁▁▃▂▁▁▂▁▂▁▁
```

**Heap InUse** (current: 153.7MB | avg: 193.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▄▃▂▅▃▅▅▄▄▄▄▃▅▄▅▃▆▁▂▁█▁▂▁▁▁▁▂▂▃▄▂▃▃▂▂▃▂▂▁▃▂▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▁▁▁▁▁▁▂▁▁▂▁▁▂▂▂▁▁▂▁▁▂▁▁▁▂▂▂▂▁▂▂▃▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,077 | 14,114 | -37 | 12,844 | 84,644 | INCREASING (+3.45/hr) |
| Heap InUse | 153.7MB | 176.9MB | -23.2MB | 193.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 853.2MB | 853.2MB | +0.0MB | 2362.6MB | 6883.9MB | |
| Heap Objects | 1,086,592 | 1,300,127 | -213535 | 861,400 | 17,165,538 | |

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
| 2026-06-06 | 238 | 16,188 | 237.2MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `aws/endpoints.init` | 2.0MB |
| 7 | `reflect.growslice` | 1.52MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 9 | `encoding/json.(*decodeState).objectInterface` | 1.0MB |
| 10 | `encoding/json.(*decodeState).literalStore` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.87GB |
| 2 | `reflect.unsafe_NewArray` | 4.5GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.93GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 3.23GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.09GB |
| 6 | `reflect.MakeSlice` | 2.55GB |
| 7 | `reflect.growslice` | 2.0GB |
| 8 | `jackskj/carta.getUniqueId` | 1.88GB |
| 9 | `fmt.Sprintf` | 1.64GB |
| 10 | `reflect.unsafe_New` | 1.62GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 314.05MB | 314.05MB | 234.61MB | 0B |
| `evaluation.mergeMetadata` | 162.54MB | 162.54MB | 121.20MB | 0B |
| `local.(*Client).EvaluateV2` | 469.90MB | 469.90MB | 348.67MB | 0B |
| `local.topologicalSort` | 61.24MB | 61.24MB | 46.06MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 463.22MB | 463.22MB | 344.52MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 50.07MB | 50.07MB | 35.36MB | 0B |
| `localEvaluation.getMapOfValue` | 463.22MB | 463.22MB | 344.52MB | 0B |
| `utils.ParseFeatureFlag` | 464.22MB | 464.22MB | 344.77MB | 0B |

**Total FF alloc (current snapshot):** 2.39GB  |  **24h avg:** 1.78GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1767 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 68.14MB | 60/1767 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1418/1767 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 35.84MB | 75/1767 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1767 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.17MB | 1418/1767 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.09MB | 1090/1767 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1767 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1767 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1767 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1767 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1767 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1767 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1767 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1767 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 29.04GB | 1181/1767 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1767 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1767 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1767 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1767 | `█░░░░░░░░░░░░░░ 10%` |

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
