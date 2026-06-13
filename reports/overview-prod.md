# Overview: prod
*Last updated: 2026-06-13 22:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T22:15 (3812 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,203 | avg: 14,601 | max: 84,644 | trend: INCREASING (+3.03/hr))
```
▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆█▅▃
```

**Heap InUse** (current: 272.0MB | avg: 240.3MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▂▁▁▂▂▂▂▃▁▄▂▁▁▂▂▃▂▁▂▂▃▁▂▂▃▁▂▁▃▁▁▃▂▁▁▁▂▂▃▁▁▁▃▁▂▂▁▂▂▁▁▂▂▁▂▁▃▃▁▂▄▂▁▁▂▂▁▂▂▂▁▁▂▂▁▃▂▃▁▁▃▁▂▃▂▂▃▁▁▁▁▆█▄▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,203 | 17,183 | -980 | 14,601 | 84,644 | INCREASING (+3.03/hr) |
| Heap InUse | 272.0MB | 296.2MB | -24.2MB | 240.3MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2288.2MB | 2284.1MB | +4.1MB | 2546.3MB | 6883.9MB | |
| Heap Objects | 981,907 | 468,146 | +513761 | 1,036,336 | 17,165,538 | |

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
| 2026-06-13 | 268 | 16,280 | 263.4MB | 1566.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `bytes.growSlice` | 21.13MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 7 | `bufio.NewWriterSize` | 5.53MB |
| 8 | `bufio.NewReaderSize` | 5.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 46.83GB |
| 2 | `reflect.growslice` | 40.3GB |
| 3 | `jackskj/carta.getUniqueId` | 36.29GB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 33.1GB |
| 5 | `reflect.unsafe_New` | 32.41GB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 27.24GB |
| 7 | `fmt.Sprintf` | 26.39GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 24.47GB |
| 9 | `reflect.unsafe_NewArray` | 24.01GB |
| 10 | `fmt.(*buffer).writeString` | 23.73GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.03GB | 2.02GB | 1.97GB | 0B |
| `evaluation.mergeMetadata` | 1.04GB | 1.04GB | 1.01GB | 0B |
| `local.(*Client).EvaluateV2` | 3.11GB | 3.11GB | 3.02GB | 0B |
| `local.topologicalSort` | 445.13MB | 444.11MB | 430.57MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.03GB | 3.02GB | 2.94GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 388.95MB | 388.45MB | 380.87MB | 0B |
| `localEvaluation.getMapOfValue` | 3.03GB | 3.02GB | 2.94GB | 0B |
| `utils.ParseFeatureFlag` | 3.04GB | 3.03GB | 2.95GB | 0B |

**Total FF alloc (current snapshot):** 16.10GB  |  **24h avg:** 15.62GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.23MB | 75/3812 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.62MB | 105/3812 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3463/3812 | `███████████░░░░ 75%` |
| 4 | `runtime.mallocgc` | 31.24MB | 3463/3812 | `█████████░░░░░░ 64%` |
| 5 | `database/sql.convertAssignRows` | 23.7MB | 125/3812 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3812 | `█████░░░░░░░░░░ 37%` |
| 7 | `bytes.growSlice` | 15.8MB | 2718/3812 | `████░░░░░░░░░░░ 32%` |
| 8 | `net/http.(*Transport).dialConn` | 13.33MB | 100/3812 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3812 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3812 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3812 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3812 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3812 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.87GB | 2004/3812 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 59.3GB | 3024/3812 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.22GB | 3186/3812 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.63GB | 3040/3812 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3812 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.17GB | 2804/3812 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.23GB | 2386/3812 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
