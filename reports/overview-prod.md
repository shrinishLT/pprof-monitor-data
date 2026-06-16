# Overview: prod
*Last updated: 2026-06-17 03:37 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T03:37 (4736 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,473 | avg: 14,875 | max: 84,644 | trend: INCREASING (+2.14/hr))
```
▁▁▁▁▂▆█▅▂▂▃▅▄▃▁▂▂▂▁▁▃▃▁▂▁▁▁▁▁▁▁▁▁▆▃▁▁▁▁▂▁▂▁▁▄▁▇▂▁▁▁▁▄▂▁▂▁▁▁▂▃▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▄▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 181.4MB | avg: 244.9MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▂▂▇▆▆▃▃▄▅▄▄▂▃▂▃▂▂▄▃▂▂▁▂▁▁▁▁▁▂▁▆▄▂▁▁▂▂▂▁▁▁▄▂█▃▂▃▂▁▄▂▁▃▁▁▁▂▄▂▁▁▁▁▂▂▁▁▁▁▁▂▁▂▃▂▂▁▁▁▁▂▁▂▅▂▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,473 | 14,177 | +1296 | 14,875 | 84,644 | INCREASING (+2.14/hr) |
| Heap InUse | 181.4MB | 139.5MB | +41.9MB | 244.9MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1004.2MB | 1005.2MB | -1.0MB | 2451.7MB | 6883.9MB | |
| Heap Objects | 497,846 | 587,478 | -89632 | 1,051,081 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 44 | 15,069 | 198.3MB | 376.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.54MB |
| 5 | `bufio.NewWriterSize` | 7.04MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.08MB |
| 7 | `bufio.NewReaderSize` | 5.52MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 22.15GB |
| 2 | `fmt.Sprintf` | 16.27GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.07GB |
| 4 | `reflect.unsafe_NewArray` | 11.55GB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 10.74GB |
| 6 | `jackskj/carta.getUniqueId` | 10.71GB |
| 7 | `reflect.growslice` | 10.24GB |
| 8 | `reflect.unsafe_New` | 9.02GB |
| 9 | `fmt.Sprint` | 8.0GB |
| 10 | `strconv.appendQuotedWith` | 7.91GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.50GB | 1.49GB | 1.40GB | 0B |
| `evaluation.mergeMetadata` | 791.19MB | 783.69MB | 733.72MB | 0B |
| `local.(*Client).EvaluateV2` | 2.31GB | 2.29GB | 2.14GB | 0B |
| `local.topologicalSort` | 321.38MB | 319.87MB | 296.07MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.21GB | 2.19GB | 2.04GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 329.96MB | 328.46MB | 316.22MB | 0B |
| `localEvaluation.getMapOfValue` | 2.21GB | 2.19GB | 2.04GB | 0B |
| `utils.ParseFeatureFlag` | 2.21GB | 2.20GB | 2.04GB | 0B |

**Total FF alloc (current snapshot):** 11.85GB  |  **24h avg:** 10.96GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4736 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4387/4736 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.39MB | 134/4736 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.53MB | 4387/4736 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.24MB | 157/4736 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4736 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.6MB | 3476/4736 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.18MB | 129/4736 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4736 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4736 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4736 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4736 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4736 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4736 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 62.19GB | 4110/4736 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.growslice` | 62.08GB | 3948/4736 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.5GB | 3964/4736 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 51.79GB | 3728/4736 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4736 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4736 | `█████░░░░░░░░░░ 37%` |

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
