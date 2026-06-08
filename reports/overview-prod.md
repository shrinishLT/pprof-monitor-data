# Overview: prod
*Last updated: 2026-06-09 00:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T00:45 (2403 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,447 | avg: 13,605 | max: 84,644 | trend: INCREASING (+4.27/hr))
```
▅█▃▁▁▄▃▃▃▂▂▁▁▁▂▆▃▂▂▂▁▂▁▁▁▁▁▁▁▃▂▁▂▂▆▃▄▂▂▆▃▂▄▂▂▃▁▁▂▁▂▃▂▁▁▁▁▂▁▁▂▅▂▁▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▂▁▁▂▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 267.7MB | avg: 211.0MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▄▅█▁▂▃▃▃▄▂▂▂▂▁▂▆▃▃▂▃▃▂▂▃▂▂▁▁▃▃▃▂▃▂▅▃▄▂▂▅▄▂▅▃▂▃▃▃▂▁▂▃▂▁▂▂▁▂▁▂▂▄▄▁▁▂▂▂▁▃▂▂▂▂▁▃▂▁▁▁▂▃▂▃▁▂▂▂▂▁▁▁▁▃▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,447 | 15,209 | -762 | 13,605 | 84,644 | INCREASING (+4.27/hr) |
| Heap InUse | 267.7MB | 330.2MB | -62.5MB | 211.0MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3343.0MB | 3342.0MB | +1.0MB | 2421.0MB | 6883.9MB | |
| Heap Objects | 1,189,744 | 1,749,908 | -560164 | 934,263 | 17,165,538 | |

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
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 10 | 14,522 | 261.7MB | 330.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `reflect.unsafe_NewArray` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 81.35GB |
| 2 | `reflect.growslice` | 66.59GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.25GB |
| 4 | `jackskj/carta.getUniqueId` | 58.12GB |
| 5 | `reflect.unsafe_New` | 52.12GB |
| 6 | `fmt.Sprintf` | 42.75GB |
| 7 | `reflect.unsafe_NewArray` | 41.6GB |
| 8 | `fmt.(*buffer).writeString` | 41.39GB |
| 9 | `carta/value.NewCell` | 37.29GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 26.57GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.50GB | 3.50GB | 3.35GB | 0B |
| `evaluation.mergeMetadata` | 1.82GB | 1.82GB | 1.75GB | 0B |
| `local.(*Client).EvaluateV2` | 5.34GB | 5.33GB | 5.11GB | 0B |
| `local.topologicalSort` | 750.89MB | 749.88MB | 722.79MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.10GB | 5.09GB | 4.87GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 741.88MB | 741.88MB | 717.67MB | 0B |
| `localEvaluation.getMapOfValue` | 5.10GB | 5.09GB | 4.87GB | 0B |
| `utils.ParseFeatureFlag` | 5.11GB | 5.10GB | 4.88GB | 0B |

**Total FF alloc (current snapshot):** 27.42GB  |  **24h avg:** 26.24GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2403 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2403 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2054/2403 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 89/2403 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 24.07MB | 2054/2403 | `████░░░░░░░░░░░ 28%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2403 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.19MB | 1525/2403 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2403 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2403 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2403 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2403 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2403 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2403 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2403 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2403 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 29.92GB | 920/2403 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2403 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2403 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 23.15GB | 1777/2403 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `reflect.growslice` | 20.97GB | 1615/2403 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
