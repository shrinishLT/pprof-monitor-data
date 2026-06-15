# Overview: prod
*Last updated: 2026-06-16 04:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T04:03 (4455 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,382 | avg: 14,800 | max: 84,644 | trend: INCREASING (+2.36/hr))
```
▃▄▄▂▄▂▃▂▂▂▂▆▄▃▁▁▁▁▃▆▄▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▄▆▂▂▃▁▁▁▄▁▁▂▅▃▁▄▇▂▁█▄▃▂▄▂▁▁▁▃▁▁▁▃▂▂▁▁▁▁▃▃▁▂▁▁▄▄▁▁▁▁▁▂▁▁▁▁▃
```

**Heap InUse** (current: 304.4MB | avg: 245.2MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▄▅▄▂▅▂▃▂▃▃▃▅▄▃▂▁▂▁▃▇▄▄▃▃▃▂▃▂▂▄▁▂▃▂▂▂▂▂▃█▂▂▄▁▁▁▃▂▂▃▄▄▂▄▆▂▃▆▅▂▃▅▃▁▂▂▂▃▁▂▂▂▂▁▁▃▂▃▄▂▂▂▂▄▅▂▂▂▁▂▃▁▁▂▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,382 | 14,691 | +1691 | 14,800 | 84,644 | INCREASING (+2.36/hr) |
| Heap InUse | 304.4MB | 286.5MB | +17.9MB | 245.2MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2429.9MB | 2431.3MB | -1.4MB | 2521.5MB | 6883.9MB | |
| Heap Objects | 1,050,581 | 1,669,486 | -618905 | 1,049,876 | 17,165,538 | |

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
| 2026-06-16 | 49 | 15,730 | 274.9MB | 455.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 22.14MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewWriterSize` | 8.06MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 8 | `bufio.NewReaderSize` | 6.53MB |
| 9 | `compress/flate.NewWriter` | 5.29MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 120.54GB |
| 2 | `reflect.growslice` | 113.43GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 110.97GB |
| 4 | `jackskj/carta.getUniqueId` | 103.48GB |
| 5 | `reflect.unsafe_New` | 90.48GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 86.61GB |
| 7 | `fmt.Sprintf` | 85.13GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 71.24GB |
| 9 | `fmt.(*buffer).writeString` | 70.11GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 65.98GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.42GB | 5.41GB | 5.27GB | 0B |
| `evaluation.mergeMetadata` | 2.81GB | 2.80GB | 2.74GB | 0B |
| `local.(*Client).EvaluateV2` | 8.34GB | 8.32GB | 8.11GB | 0B |
| `local.topologicalSort` | 1.18GB | 1.18GB | 1.15GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.07GB | 8.05GB | 7.84GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.05GB | 1.05GB | 1.03GB | 0B |
| `localEvaluation.getMapOfValue` | 8.07GB | 8.05GB | 7.84GB | 0B |
| `utils.ParseFeatureFlag` | 8.08GB | 8.06GB | 7.85GB | 0B |

**Total FF alloc (current snapshot):** 43.02GB  |  **24h avg:** 41.82GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 41.95MB | 91/4455 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.75MB | 124/4455 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4106/4455 | `█████████████░░ 87%` |
| 4 | `runtime.mallocgc` | 31.36MB | 4106/4455 | `███████████░░░░ 74%` |
| 5 | `database/sql.convertAssignRows` | 21.51MB | 145/4455 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4455 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.75MB | 3221/4455 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.21MB | 119/4455 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4455 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4455 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4455 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4455 | `████████░░░░░░░ 59%` |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 74.53GB | 2644/4455 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4455 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.53GB | 3667/4455 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.34GB | 3829/4455 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.73GB | 3683/4455 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.21GB | 3447/4455 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4455 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.6GB | 3001/4455 | `█████░░░░░░░░░░ 38%` |

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
