# Overview: prod
*Last updated: 2026-06-16 23:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T23:21 (4685 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,784 | avg: 14,871 | max: 84,644 | trend: INCREASING (+2.20/hr))
```
▁▁▂▁▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▂▂▁▁▁▁▂▆█▅▂▂▃▅▄▃▁▂▂▂▁▁▃▃▁▂▁▁▁▁▁▁▁▁▁▆▃▁▁▁▁▂▁▁▁▁▄
```

**Heap InUse** (current: 323.1MB | avg: 245.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▃▂▃▂▂▂▁▁▁▂▂▁▁▁▁▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂▂▂▄▂▂▁▁▁▁▂▂▂▂▂▁▁▂▂▂▁▁▂▂▃█▇▆▄▃▄▅▄▄▂▃▂▃▂▂▄▄▂▂▁▂▁▂▂▂▁▂▁▆▄▂▂▂▂▂▂▂▁▁▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,784 | 14,303 | +4481 | 14,871 | 84,644 | INCREASING (+2.20/hr) |
| Heap InUse | 323.1MB | 176.2MB | +146.9MB | 245.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 993.3MB | 994.2MB | -0.9MB | 2467.5MB | 6883.9MB | |
| Heap Objects | 902,821 | 911,057 | -8236 | 1,052,125 | 17,165,538 | |

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
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 279 | 16,158 | 252.6MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 28.2MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 17.08MB |
| 4 | `bufio.NewReaderSize` | 15.05MB |
| 5 | `runtime.mallocgc` | 14.01MB |
| 6 | `bufio.NewWriterSize` | 9.53MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 10 | `net/http.(*Transport).dialConn` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.35GB |
| 2 | `fmt.Sprintf` | 12.43GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 8.91GB |
| 4 | `reflect.unsafe_NewArray` | 8.57GB |
| 5 | `jackskj/carta.getUniqueId` | 8.29GB |
| 6 | `reflect.growslice` | 7.68GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.3GB |
| 8 | `reflect.unsafe_New` | 6.75GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.46GB |
| 10 | `fmt.Sprint` | 6.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.27GB | 1.27GB | 1.09GB | 0B |
| `evaluation.mergeMetadata` | 665.66MB | 662.66MB | 573.57MB | 0B |
| `local.(*Client).EvaluateV2` | 1.93GB | 1.92GB | 1.66GB | 0B |
| `local.topologicalSort` | 263.20MB | 262.20MB | 226.18MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.83GB | 1.81GB | 1.56GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 300.27MB | 298.26MB | 270.21MB | 0B |
| `localEvaluation.getMapOfValue` | 1.83GB | 1.81GB | 1.56GB | 0B |
| `utils.ParseFeatureFlag` | 1.83GB | 1.82GB | 1.56GB | 512.56kB |

**Total FF alloc (current snapshot):** 9.89GB  |  **24h avg:** 8.48GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4685 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4336/4685 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.6MB | 133/4685 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.72MB | 4336/4685 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.35MB | 156/4685 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4685 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.67MB | 3435/4685 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.18MB | 129/4685 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4685 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4685 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4685 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4685 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4685 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4685 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 62.78GB | 3897/4685 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.73GB | 4059/4685 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.11GB | 3913/4685 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 52.4GB | 3677/4685 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4685 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4685 | `█████░░░░░░░░░░ 37%` |

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
