# Overview: prod
*Last updated: 2026-06-04 05:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T05:05 (1016 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,164 | avg: 10,293 | max: 84,644 | trend: decreasing (-32.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆
```

**Heap InUse** (current: 324.4MB | avg: 154.2MB | max: 2823.8MB | trend: stable (-0.47MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,164 | 15,689 | +2475 | 10,293 | 84,644 | decreasing (-32.91/hr) |
| Heap InUse | 324.4MB | 256.4MB | +68.0MB | 154.2MB | 2823.8MB | stable (-0.47MB/hr) |
| Heap Sys | 937.6MB | 936.8MB | +0.8MB | 2566.6MB | 6883.9MB | |
| Heap Objects | 1,451,101 | 1,103,626 | +347475 | 660,361 | 14,090,816 | |

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
| 2026-06-04 | 62 | 15,593 | 269.6MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 39.33MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 13.51MB |
| 4 | `bufio.NewWriterSize` | 10.54MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 7.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 7.06MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 4.43GB |
| 2 | `fmt.Sprintf` | 4.26GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 3.24GB |
| 4 | `jackskj/carta.getUniqueId` | 2.99GB |
| 5 | `reflect.growslice` | 2.91GB |
| 6 | `reflect.unsafe_New` | 2.54GB |
| 7 | `fmt.(*buffer).writeString` | 2.32GB |
| 8 | `strconv.appendQuotedWith` | 2.08GB |
| 9 | `fmt.Sprint` | 2.0GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 1.94GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 35.14MB | 31.09MB | 78.86MB | 0B |
| `evaluation.mergeMetadata` | 18.50MB | 16.00MB | 40.85MB | 0B |
| `local.(*Client).EvaluateV2` | 48.95MB | 42.86MB | 122.11MB | 0B |
| `local.topologicalSort` | 8.08MB | 7.06MB | 19.77MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 53.59MB | 46.48MB | 117.59MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 512.14kB | 512.14kB | 11.58MB | 0B |
| `localEvaluation.getMapOfValue` | 53.59MB | 46.48MB | 117.59MB | 0B |
| `utils.ParseFeatureFlag` | 53.59MB | 46.48MB | 117.59MB | 0B |

**Total FF alloc (current snapshot):** 271.96MB  |  **24h avg:** 625.94MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 69.34MB | 28/1016 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1016 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 667/1016 | `███████░░░░░░░░ 52%` |
| 4 | `database/sql.convertAssignRows` | 34.25MB | 36/1016 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.34MB | 667/1016 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1016 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 13.35MB | 474/1016 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 18/1016 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1016 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1016 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1016 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1016 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1016 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1016 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1016 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.53GB | 644/1016 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1016 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.8GB | 582/1016 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.63GB | 334/1016 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1016 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.2x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Goroutine spike to 20,625 at 2026-05-18T12:33 (2.0x avg)
