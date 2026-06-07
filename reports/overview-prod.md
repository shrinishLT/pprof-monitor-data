# Overview: prod
*Last updated: 2026-06-07 23:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T23:55 (2105 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,095 | avg: 13,228 | max: 84,644 | trend: INCREASING (+3.89/hr))
```
▅█▁▁▂▁▄▂▂▁▁▁▁▃▁▁▁▃▁▁▁▁▁▁▁▄▁▁▁▃▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▂▁▁▂▁▂▁▁▂▃▂▁▃▂▂▅▃▂▂▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▂▁▁▁▁▄▆▂▁▁▁
```

**Heap InUse** (current: 224.0MB | avg: 197.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
█▅▁▃▃▆▆▄▄▁▆▂▆▂▁▄▄▃▅▁▃▄▃▄▅▂▁▄▁▂▂▃▄▄▃▁▁▅▆▅▁▆▂▁▆▅▂▃▂▂▅▅▂▅▂▃▃▂▃▃▅▇▆▃▃▆▂▆▂▃▂▃▃▅▅▄▄▄▅▅▅▄▁▂▂▂▂▇▅▄▅▇▅▄▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,095 | 14,187 | -92 | 13,228 | 84,644 | INCREASING (+3.89/hr) |
| Heap InUse | 224.0MB | 267.0MB | -43.0MB | 197.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3221.4MB | 3221.4MB | +0.0MB | 2302.8MB | 6883.9MB | |
| Heap Objects | 1,201,756 | 1,561,123 | -359367 | 891,953 | 17,165,538 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 47.32GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.04GB |
| 3 | `reflect.growslice` | 34.47GB |
| 4 | `jackskj/carta.getUniqueId` | 29.59GB |
| 5 | `reflect.unsafe_New` | 26.62GB |
| 6 | `reflect.unsafe_NewArray` | 24.18GB |
| 7 | `fmt.(*buffer).writeString` | 21.37GB |
| 8 | `carta/value.NewCell` | 19.03GB |
| 9 | `fmt.Sprintf` | 17.11GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 16.9GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.29GB | 1.29GB | 1.23GB | 0B |
| `evaluation.mergeMetadata` | 682.17MB | 681.16MB | 649.87MB | 0B |
| `local.(*Client).EvaluateV2` | 1.96GB | 1.95GB | 1.86GB | 0B |
| `local.topologicalSort` | 262.18MB | 262.18MB | 250.84MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.94GB | 1.94GB | 1.85GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 218.26MB | 216.71MB | 203.21MB | 0B |
| `localEvaluation.getMapOfValue` | 1.94GB | 1.94GB | 1.85GB | 0B |
| `utils.ParseFeatureFlag` | 1.94GB | 1.94GB | 1.86GB | 0B |

**Total FF alloc (current snapshot):** 10.21GB  |  **24h avg:** 9.74GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2105 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2105 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1756/2105 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 32.64MB | 83/2105 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 19.66MB | 1756/2105 | `███░░░░░░░░░░░░ 22%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2105 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.78MB | 1278/2105 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2105 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2105 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2105 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2105 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2105 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2105 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2105 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2105 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2105 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2105 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.82GB | 622/2105 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `segmentio/kafka-go.makePartitions` | 14.84GB | 1479/2105 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2105 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
