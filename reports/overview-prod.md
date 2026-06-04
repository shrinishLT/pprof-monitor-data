# Overview: prod
*Last updated: 2026-06-04 09:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T09:20 (1067 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,770 | avg: 10,501 | max: 84,644 | trend: decreasing (-26.19/hr))
```
█▃▁▁▁▁▁▁▁▃▁▃▂▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▃▂▃▅▁▁▁▁▃▁▁▁▁▃▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 190.9MB | avg: 156.0MB | max: 2823.8MB | trend: stable (-0.38MB/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,770 | 14,563 | +207 | 10,501 | 84,644 | decreasing (-26.19/hr) |
| Heap InUse | 190.9MB | 131.4MB | +59.5MB | 156.0MB | 2823.8MB | stable (-0.38MB/hr) |
| Heap Sys | 5127.3MB | 5128.4MB | -1.1MB | 2593.5MB | 6883.9MB | |
| Heap Objects | 898,474 | 263,800 | +634674 | 672,706 | 14,090,816 | |

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
| 2026-06-04 | 113 | 15,162 | 235.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `bufio.NewReaderSize` | 3.54MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 9 | `bufio.NewWriterSize` | 3.03MB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 2.93MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 7.35GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.09GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.17GB |
| 6 | `jackskj/carta.getUniqueId` | 6.12GB |
| 7 | `database/sql.convertAssignRows` | 5.83GB |
| 8 | `reflect.unsafe_New` | 5.54GB |
| 9 | `segmentio/kafka-go.makePartitions` | 5.24GB |
| 10 | `fmt.(*buffer).writeString` | 4.27GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 226.34MB | 218.76MB | 116.82MB | 0B |
| `evaluation.mergeMetadata` | 115.03MB | 112.53MB | 62.74MB | 0B |
| `local.(*Client).EvaluateV2` | 348.36MB | 332.01MB | 174.25MB | 0B |
| `local.topologicalSort` | 49.61MB | 44.53MB | 23.09MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 347.76MB | 329.88MB | 173.94MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 33.85MB | 33.35MB | 18.37MB | 0B |
| `localEvaluation.getMapOfValue` | 347.76MB | 329.88MB | 173.94MB | 0B |
| `utils.ParseFeatureFlag` | 348.26MB | 330.38MB | 174.26MB | 0B |

**Total FF alloc (current snapshot):** 1.77GB  |  **24h avg:** 917.42MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1067 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1067 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 718/1067 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1067 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.72MB | 718/1067 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1067 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 12.92MB | 507/1067 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1067 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1067 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1067 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1067 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1067 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1067 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1067 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1067 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.81GB | 691/1067 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1067 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.5GB | 622/1067 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1067 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.19GB | 457/1067 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.1x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
