# Overview: prod
*Last updated: 2026-06-14 06:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T06:25 (3910 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,578 | avg: 14,633 | max: 84,644 | trend: INCREASING (+2.90/hr))
```
▆▇█▅▅▅▅▆▆▅▆▅▆▄▅▂▃▄▄▅▄▄▅▅▅▄▆▅▅▅▅▅▅▅▆▆▅▆▅▆▆▇▇▇▅▆▅▅▅▄▄▄▄▅▆▆▅▆▄▅▅▆▆▄▅▅▆▄▇▅▃▃▃▄▃▄▃▄▇▅▄▂▄▄▄▁▁▁▁▁▁▂▂▂▂▆
```

**Heap InUse** (current: 374.3MB | avg: 241.3MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▃▂▃▃▂▃▂▃▄▂▃▂▃▂▂▂▁▂▂▃▁▁▂▂▃▂▄▃▂▃▃▂▂▄▂▃▃▄▃▂▃▃▂▃▃▃▄▂▂▂▂▂▂▃▄▃▂▃▃▂▂▄▂▂▂▄▃▃▃▃█▃▂▂▂▂▂▂▂▄▃▂▃▂▁▁▁▁▁▁▁▁▂▁▃▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,578 | 14,968 | +1610 | 14,633 | 84,644 | INCREASING (+2.90/hr) |
| Heap InUse | 374.3MB | 296.7MB | +77.6MB | 241.3MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2296.9MB | 2297.1MB | -0.2MB | 2540.0MB | 6883.9MB | |
| Heap Objects | 1,844,307 | 1,118,999 | +725308 | 1,036,514 | 17,165,538 | |

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
| 2026-06-14 | 78 | 15,830 | 280.4MB | 547.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `bytes.growSlice` | 22.63MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewWriterSize` | 7.53MB |
| 7 | `bufio.NewReaderSize` | 7.03MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 5.08MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 59.16GB |
| 2 | `segmentio/kafka-go.makePartitions` | 58.15GB |
| 3 | `jackskj/carta.getUniqueId` | 54.29GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 53.82GB |
| 5 | `reflect.unsafe_New` | 47.28GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 44.69GB |
| 7 | `fmt.Sprintf` | 44.58GB |
| 8 | `fmt.(*buffer).writeString` | 37.13GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 36.75GB |
| 10 | `carta/value.NewCell` | 34.15GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.42GB | 2.42GB | 2.34GB | 0B |
| `evaluation.mergeMetadata` | 1.24GB | 1.24GB | 1.21GB | 0B |
| `local.(*Client).EvaluateV2` | 3.72GB | 3.72GB | 3.60GB | 0B |
| `local.topologicalSort` | 543.83MB | 543.83MB | 525.72MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.65GB | 3.65GB | 3.53GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 435.49MB | 435.49MB | 428.03MB | 0B |
| `localEvaluation.getMapOfValue` | 3.65GB | 3.65GB | 3.53GB | 0B |
| `utils.ParseFeatureFlag` | 3.66GB | 3.66GB | 3.54GB | 0B |

**Total FF alloc (current snapshot):** 19.31GB  |  **24h avg:** 18.68GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 77/3910 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 41.91MB | 107/3910 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3561/3910 | `███████████░░░░ 77%` |
| 4 | `runtime.mallocgc` | 31.23MB | 3561/3910 | `█████████░░░░░░ 66%` |
| 5 | `database/sql.convertAssignRows` | 23.39MB | 127/3910 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3910 | `█████░░░░░░░░░░ 38%` |
| 7 | `bytes.growSlice` | 15.74MB | 2813/3910 | `█████░░░░░░░░░░ 33%` |
| 8 | `net/http.(*Transport).dialConn` | 13.13MB | 102/3910 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3910 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3910 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3910 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3910 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3910 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.41GB | 2099/3910 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.02GB | 3284/3910 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 58.9GB | 3122/3910 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.34GB | 3138/3910 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3910 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.75GB | 2902/3910 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/3910 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
