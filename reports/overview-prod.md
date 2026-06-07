# Overview: prod
*Last updated: 2026-06-08 02:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T02:10 (2132 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,322 | avg: 13,244 | max: 84,644 | trend: INCREASING (+3.83/hr))
```
▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▂▂▂▁▂▁▂▄▂▂▂▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▃▄▁▁▁▁▁▆▆▄▅▁▁▁▁▁▁▁▂▂▂▂▅▂▂▄▂▂▃▇█▅▂
```

**Heap InUse** (current: 261.4MB | avg: 198.2MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▄▁▂▂▃▄▄▃▁▁▅▆▅▁▆▂▁▆▅▂▃▂▂▅▅▂▅▂▃▃▂▃▃▅▇▆▃▃▆▂▆▂▃▂▃▃▅▅▄▄▄▅▅▅▄▁▂▂▂▂▇▅▄▅█▅▄▅▃▄▆▄▆▇▃▃▂▂▁▁▂▄▂▃▁▅▃▂▃▂▂▃▇▆▃▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,322 | 14,923 | -601 | 13,244 | 84,644 | INCREASING (+3.83/hr) |
| Heap InUse | 261.4MB | 224.0MB | +37.4MB | 198.2MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3222.8MB | 3223.1MB | -0.3MB | 2314.5MB | 6883.9MB | |
| Heap Objects | 1,293,579 | 651,437 | +642142 | 892,217 | 17,165,538 | |

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
| 2026-06-08 | 27 | 14,487 | 227.7MB | 300.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bytes.growSlice` | 3.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.51MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 50.36GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 41.05GB |
| 3 | `reflect.growslice` | 36.21GB |
| 4 | `jackskj/carta.getUniqueId` | 31.1GB |
| 5 | `reflect.unsafe_New` | 28.15GB |
| 6 | `reflect.unsafe_NewArray` | 25.76GB |
| 7 | `fmt.(*buffer).writeString` | 22.27GB |
| 8 | `carta/value.NewCell` | 20.07GB |
| 9 | `fmt.Sprintf` | 18.48GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 17.83GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.35GB | 1.35GB | 1.30GB | 0B |
| `evaluation.mergeMetadata` | 715.17MB | 715.17MB | 686.46MB | 0B |
| `local.(*Client).EvaluateV2` | 2.05GB | 2.04GB | 1.97GB | 0B |
| `local.topologicalSort` | 272.35MB | 272.35MB | 262.74MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.03GB | 2.03GB | 1.95GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 223.40MB | 223.40MB | 216.72MB | 0B |
| `localEvaluation.getMapOfValue` | 2.03GB | 2.03GB | 1.95GB | 0B |
| `utils.ParseFeatureFlag` | 2.04GB | 2.04GB | 1.96GB | 0B |

**Total FF alloc (current snapshot):** 10.68GB  |  **24h avg:** 10.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2132 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2132 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1783/2132 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 32.28MB | 84/2132 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 20.11MB | 1783/2132 | `███░░░░░░░░░░░░ 23%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2132 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.64MB | 1295/2132 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2132 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2132 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2132 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2132 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2132 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2132 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2132 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2132 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2132 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2132 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.71GB | 649/2132 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `segmentio/kafka-go.makePartitions` | 15.45GB | 1506/2132 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2132 | `█░░░░░░░░░░░░░░ 11%` |

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
