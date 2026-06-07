# Overview: prod
*Last updated: 2026-06-07 14:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T14:50 (1996 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,374 | avg: 13,171 | max: 84,644 | trend: INCREASING (+4.20/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▆▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 267.5MB | avg: 195.7MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▇▅▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,374 | 14,224 | +150 | 13,171 | 84,644 | INCREASING (+4.20/hr) |
| Heap InUse | 267.5MB | 199.3MB | +68.2MB | 195.7MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3218.0MB | 3217.9MB | +0.1MB | 2252.7MB | 6883.9MB | |
| Heap Objects | 1,268,728 | 674,843 | +593885 | 881,292 | 17,165,538 | |

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
| 2026-06-07 | 179 | 16,119 | 233.5MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bytes.growSlice` | 2.57MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 39.94GB |
| 2 | `segmentio/kafka-go.makePartitions` | 34.95GB |
| 3 | `reflect.growslice` | 33.74GB |
| 4 | `jackskj/carta.getUniqueId` | 29.03GB |
| 5 | `reflect.unsafe_New` | 26.04GB |
| 6 | `fmt.(*buffer).writeString` | 21.1GB |
| 7 | `carta/value.NewCell` | 18.69GB |
| 8 | `reflect.unsafe_NewArray` | 17.89GB |
| 9 | `fmt.Sprintf` | 15.53GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 13.84GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 995.82MB | 994.82MB | 898.10MB | 0B |
| `evaluation.mergeMetadata` | 509.62MB | 508.62MB | 460.14MB | 0B |
| `local.(*Client).EvaluateV2` | 1.48GB | 1.48GB | 1.33GB | 0B |
| `local.topologicalSort` | 204.95MB | 203.94MB | 184.55MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.52GB | 1.52GB | 1.38GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 119.14MB | 118.64MB | 104.76MB | 0B |
| `localEvaluation.getMapOfValue` | 1.52GB | 1.52GB | 1.38GB | 0B |
| `utils.ParseFeatureFlag` | 1.53GB | 1.52GB | 1.38GB | 0B |

**Total FF alloc (current snapshot):** 7.84GB  |  **24h avg:** 7.08GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1996 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1996 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1647/1996 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1996 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1996 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.68MB | 1647/1996 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.34MB | 1220/1996 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.79MB | 36/1996 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1996 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/1996 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1996 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1996 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1996 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1996 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1996 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1996 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1996 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 14.32GB | 513/1996 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1996 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.74GB | 1370/1996 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
