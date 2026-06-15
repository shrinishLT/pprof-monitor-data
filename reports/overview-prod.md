# Overview: prod
*Last updated: 2026-06-15 15:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T15:50 (4311 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,561 | avg: 14,764 | max: 84,644 | trend: INCREASING (+2.50/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▃▅▆▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 497.3MB | avg: 243.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▄▄▆▆█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,561 | 19,534 | +27 | 14,764 | 84,644 | INCREASING (+2.50/hr) |
| Heap InUse | 497.3MB | 457.5MB | +39.8MB | 243.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2418.8MB | 2421.2MB | -2.4MB | 2524.7MB | 6883.9MB | |
| Heap Objects | 2,334,713 | 2,086,036 | +248677 | 1,046,481 | 17,165,538 | |

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
| 2026-06-15 | 191 | 16,235 | 277.2MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 49.54MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 32.36MB |
| 4 | `bufio.NewReaderSize` | 17.09MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.58MB |
| 6 | `bufio.NewWriterSize` | 11.56MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 6.0MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 5.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 109.56GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.33GB |
| 3 | `segmentio/kafka-go.makePartitions` | 103.85GB |
| 4 | `jackskj/carta.getUniqueId` | 99.24GB |
| 5 | `reflect.unsafe_New` | 86.83GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 78.37GB |
| 7 | `fmt.Sprintf` | 70.21GB |
| 8 | `fmt.(*buffer).writeString` | 67.54GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 64.51GB |
| 10 | `carta/value.NewCell` | 62.89GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.14GB | 4.13GB | 3.91GB | 0B |
| `evaluation.mergeMetadata` | 2.14GB | 2.14GB | 2.02GB | 0B |
| `local.(*Client).EvaluateV2` | 6.37GB | 6.35GB | 6.01GB | 0B |
| `local.topologicalSort` | 925.86MB | 922.33MB | 868.60MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.24GB | 6.22GB | 5.91GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 769.68MB | 765.59MB | 703.48MB | 0B |
| `localEvaluation.getMapOfValue` | 6.24GB | 6.22GB | 5.91GB | 0B |
| `utils.ParseFeatureFlag` | 6.25GB | 6.23GB | 5.92GB | 0B |

**Total FF alloc (current snapshot):** 33.03GB  |  **24h avg:** 31.21GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.12MB | 88/4311 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.23MB | 122/4311 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3962/4311 | `████████████░░░ 84%` |
| 4 | `runtime.mallocgc` | 31.32MB | 3962/4311 | `██████████░░░░░ 72%` |
| 5 | `database/sql.convertAssignRows` | 21.72MB | 143/4311 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4311 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.82MB | 3084/4311 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.44MB | 116/4311 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4311 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4311 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4311 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4311 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4311 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.49GB | 2500/4311 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 61.6GB | 3523/4311 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.43GB | 3685/4311 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 54.94GB | 3539/4311 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 51.68GB | 3303/4311 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4311 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.54GB | 2857/4311 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
