# Overview: prod
*Last updated: 2026-06-15 23:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T23:15 (4398 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,238 | avg: 14,788 | max: 84,644 | trend: INCREASING (+2.42/hr))
```
▂▅▂▁▁▂▇▆▆▄▄▇▂▂▂▃▂▂▁▁▁▃▂▃▂▂▂▂▂▂▁▁▁▁▂▆▄▁▂▂▃▄▂▃▂▄▃▃▁▄▁█▃▃▁▁▂▄▄▄▂▄▂▃▂▃▂▂▇▅▃▁▁▁▁▄▇▄▃▂▁▁▂▁▁▁▂▁▁▁▁▁▁▂▁▄
```

**Heap InUse** (current: 291.6MB | avg: 244.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▃▄▃▂▂▂▅▆▇▅▅▅▃▂▂▂▃▃▃▁▁▃▂▃▂▂▂▂▃▃▂▂▁▃▂▆▄▂▂▃▃▃▂▄▄▆▃▄▁▄▂▆▃▃▂▁▂▄▅▄▂▅▂▃▂▂▃▃▅▄▃▁▁▂▁▃█▄▄▃▃▃▂▃▂▂▄▁▂▃▂▁▁▂▁▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,238 | 14,753 | +2485 | 14,788 | 84,644 | INCREASING (+2.42/hr) |
| Heap InUse | 291.6MB | 226.8MB | +64.8MB | 244.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2426.9MB | 2428.0MB | -1.1MB | 2522.8MB | 6883.9MB | |
| Heap Objects | 965,926 | 1,028,991 | -63065 | 1,048,821 | 17,165,538 | |

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
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 278 | 16,148 | 281.9MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 19.6MB |
| 4 | `bufio.NewReaderSize` | 9.54MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `bufio.NewWriterSize` | 7.04MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 113.94GB |
| 2 | `reflect.growslice` | 110.65GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.85GB |
| 4 | `jackskj/carta.getUniqueId` | 100.73GB |
| 5 | `reflect.unsafe_New` | 88.02GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 82.47GB |
| 7 | `fmt.Sprintf` | 79.38GB |
| 8 | `fmt.(*buffer).writeString` | 68.41GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 67.85GB |
| 10 | `carta/value.NewCell` | 63.65GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.05GB | 5.04GB | 4.85GB | 0B |
| `evaluation.mergeMetadata` | 2.63GB | 2.63GB | 2.52GB | 0B |
| `local.(*Client).EvaluateV2` | 7.76GB | 7.75GB | 7.45GB | 0B |
| `local.topologicalSort` | 1.09GB | 1.09GB | 1.05GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.51GB | 7.50GB | 7.23GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1014.56MB | 1013.56MB | 962.61MB | 0B |
| `localEvaluation.getMapOfValue` | 7.51GB | 7.50GB | 7.23GB | 0B |
| `utils.ParseFeatureFlag` | 7.52GB | 7.51GB | 7.24GB | 0B |

**Total FF alloc (current snapshot):** 40.06GB  |  **24h avg:** 38.51GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.36MB | 90/4398 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.02MB | 123/4398 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4049/4398 | `████████████░░░ 86%` |
| 4 | `runtime.mallocgc` | 31.35MB | 4049/4398 | `███████████░░░░ 74%` |
| 5 | `database/sql.convertAssignRows` | 21.51MB | 145/4398 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4398 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.8MB | 3169/4398 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.28MB | 118/4398 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4398 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4398 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4398 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4398 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4398 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.74GB | 2587/4398 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 62.77GB | 3610/4398 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.52GB | 3772/4398 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 56.02GB | 3626/4398 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 52.6GB | 3390/4398 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4398 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.18GB | 2944/4398 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
