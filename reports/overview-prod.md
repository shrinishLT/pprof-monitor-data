# Overview: prod
*Last updated: 2026-06-08 05:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T05:25 (2171 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,149 | avg: 13,265 | max: 84,644 | trend: INCREASING (+3.74/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▄▄▂▃▁▁▁▁▁▁▁▁▂▁▁▃▁▂▃▁▁▂▄▅▃▁▃▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▃▂▂▂▁▃▂▃▁▁▁▁▂▁▁▁▁▂▃▁▃█
```

**Heap InUse** (current: 271.6MB | avg: 198.9MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▆▂▃▂▃▃▅▅▄▃▄▅▅▄▄▁▁▂▂▂▇▅▄▄▇▅▄▅▃▄▆▄▆▇▃▂▁▁▁▁▁▃▁▃▁▄▂▂▃▂▁▃▇▅▃▅█▁▄▅▆▆▃▅▁▃▂▂▂▃▆▅▂▅▄▃▂▆▃▄▆▁▂▁▄▃▁▃▅▃▆▆▅▆▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,149 | 14,857 | +1292 | 13,265 | 84,644 | INCREASING (+3.74/hr) |
| Heap InUse | 271.6MB | 279.3MB | -7.7MB | 198.9MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3224.0MB | 3226.1MB | -2.1MB | 2330.8MB | 6883.9MB | |
| Heap Objects | 697,370 | 1,346,248 | -648878 | 895,810 | 17,165,538 | |

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
| 2026-06-08 | 66 | 14,433 | 235.5MB | 310.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 18.1MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `reflect.growslice` | 9.17MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `fmt.(*buffer).writeString` | 6.08MB |
| 8 | `bufio.NewWriterSize` | 6.02MB |
| 9 | `bufio.NewReaderSize` | 5.02MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 54.77GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 42.81GB |
| 3 | `reflect.growslice` | 42.7GB |
| 4 | `jackskj/carta.getUniqueId` | 35.94GB |
| 5 | `reflect.unsafe_New` | 32.67GB |
| 6 | `reflect.unsafe_NewArray` | 28.03GB |
| 7 | `fmt.(*buffer).writeString` | 26.68GB |
| 8 | `carta/value.NewCell` | 23.31GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 19.76GB |
| 10 | `fmt.Sprintf` | 19.51GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.47GB | 1.47GB | 1.40GB | 0B |
| `evaluation.mergeMetadata` | 781.69MB | 781.69MB | 741.49MB | 0B |
| `local.(*Client).EvaluateV2` | 2.23GB | 2.23GB | 2.12GB | 0B |
| `local.topologicalSort` | 305.23MB | 303.71MB | 284.74MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.22GB | 2.22GB | 2.11GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 234.13MB | 234.13MB | 226.82MB | 0B |
| `localEvaluation.getMapOfValue` | 2.22GB | 2.22GB | 2.11GB | 0B |
| `utils.ParseFeatureFlag` | 2.23GB | 2.23GB | 2.11GB | 0B |

**Total FF alloc (current snapshot):** 11.67GB  |  **24h avg:** 11.07GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2171 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2171 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1822/2171 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.61MB | 86/2171 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 20.74MB | 1822/2171 | `███░░░░░░░░░░░░ 24%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2171 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.45MB | 1319/2171 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2171 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2171 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2171 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2171 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2171 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2171 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2171 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2171 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2171 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2171 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.93GB | 688/2171 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `segmentio/kafka-go.makePartitions` | 16.39GB | 1545/2171 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `reflect.growslice` | 14.33GB | 1383/2171 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
