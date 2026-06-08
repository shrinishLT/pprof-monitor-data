# Overview: prod
*Last updated: 2026-06-08 22:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T22:35 (2377 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,536 | avg: 13,594 | max: 84,644 | trend: INCREASING (+4.35/hr))
```
▇▆▇▅▃▄▄▃▂▃▃▄▃▂▄▃▄▅▃▂▁▁▄▆▅▄▅█▃▁▁▄▃▃▃▂▁▁▁▁▁▆▂▂▂▂▁▂▁▁▁▁▁▁▁▃▂▁▂▂▆▃▄▂▂▆▃▂▄▂▂▂▁▁▁▁▂▂▂▁▁▁▁▂▁▁▂▅▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 300.6MB | avg: 210.5MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▃▃▂▂▂▂▂▂▁▁▂▂▂▁█▁▂▂▂▁▁▁▂▃▃▂▂▂▄▁▁▂▁▁▂▁▁▁▁▁▁▃▂▁▁▁▂▁▁▁▁▁▁▁▁▂▂▁▂▁▃▂▂▁▁▃▂▁▂▂▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,536 | 14,180 | +356 | 13,594 | 84,644 | INCREASING (+4.35/hr) |
| Heap InUse | 300.6MB | 216.7MB | +83.9MB | 210.5MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3340.0MB | 3340.3MB | -0.3MB | 2411.0MB | 6883.9MB | |
| Heap Objects | 1,905,928 | 1,051,633 | +854295 | 930,730 | 17,165,538 | |

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
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 272 | 16,421 | 308.4MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.55MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 2.14MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 78.38GB |
| 2 | `reflect.growslice` | 66.11GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.19GB |
| 4 | `jackskj/carta.getUniqueId` | 57.58GB |
| 5 | `reflect.unsafe_New` | 51.71GB |
| 6 | `fmt.Sprintf` | 41.87GB |
| 7 | `fmt.(*buffer).writeString` | 41.12GB |
| 8 | `reflect.unsafe_NewArray` | 40.02GB |
| 9 | `carta/value.NewCell` | 37.0GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 25.54GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.34GB | 3.33GB | 3.12GB | 0B |
| `evaluation.mergeMetadata` | 1.74GB | 1.74GB | 1.63GB | 0B |
| `local.(*Client).EvaluateV2` | 5.09GB | 5.08GB | 4.75GB | 0B |
| `local.topologicalSort` | 722.54MB | 722.03MB | 671.33MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.86GB | 4.84GB | 4.54GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 719.32MB | 718.82MB | 659.83MB | 0B |
| `localEvaluation.getMapOfValue` | 4.86GB | 4.84GB | 4.54GB | 0B |
| `utils.ParseFeatureFlag` | 4.86GB | 4.85GB | 4.55GB | 0B |

**Total FF alloc (current snapshot):** 26.17GB  |  **24h avg:** 24.44GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2377 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2377 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2028/2377 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 89/2377 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 23.73MB | 2028/2377 | `████░░░░░░░░░░░ 27%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2377 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.32MB | 1504/2377 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2377 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2377 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2377 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2377 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2377 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2377 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2377 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2377 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 29.04GB | 894/2377 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2377 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2377 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 22.3GB | 1751/2377 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `reflect.growslice` | 20.23GB | 1589/2377 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.6x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
