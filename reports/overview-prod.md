# Overview: prod
*Last updated: 2026-06-13 01:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T01:05 (3558 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 25,163 | avg: 14,477 | max: 84,644 | trend: INCREASING (+3.29/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆▅▆▅▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄
```

**Heap InUse** (current: 474.9MB | avg: 238.5MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆█▄▄▅▃▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▄
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 29%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 25,163 | 14,427 | +10736 | 14,477 | 84,644 | INCREASING (+3.29/hr) |
| Heap InUse | 474.9MB | 212.6MB | +262.3MB | 238.5MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1169.4MB | 1183.9MB | -14.5MB | 2598.8MB | 6883.9MB | |
| Heap Objects | 2,513,721 | 1,177,281 | +1336440 | 1,025,461 | 17,165,538 | |

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
| 2026-06-13 | 14 | 15,359 | 221.1MB | 474.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 45.3MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewWriterSize` | 18.57MB |
| 4 | `runtime.mallocgc` | 18.22MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 17.08MB |
| 6 | `bufio.NewReaderSize` | 16.07MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 6.01MB |
| 10 | `compress/flate.NewWriter` | 5.29MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 17.99GB |
| 2 | `fmt.Sprintf` | 12.17GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.2GB |
| 4 | `reflect.unsafe_NewArray` | 9.2GB |
| 5 | `jackskj/carta.getUniqueId` | 8.95GB |
| 6 | `reflect.growslice` | 8.89GB |
| 7 | `reflect.unsafe_New` | 7.78GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.59GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 7.24GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.16GB | 1.15GB | 1.03GB | 0B |
| `evaluation.mergeMetadata` | 604.65MB | 600.65MB | 537.17MB | 0B |
| `local.(*Client).EvaluateV2` | 1.78GB | 1.77GB | 1.58GB | 0B |
| `local.topologicalSort` | 258.20MB | 256.68MB | 231.82MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.66GB | 1.65GB | 1.46GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 272.66MB | 272.66MB | 257.15MB | 0B |
| `localEvaluation.getMapOfValue` | 1.66GB | 1.65GB | 1.46GB | 0B |
| `utils.ParseFeatureFlag` | 1.66GB | 1.65GB | 1.47GB | 0B |

**Total FF alloc (current snapshot):** 9.02GB  |  **24h avg:** 8.00GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.24MB | 70/3558 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.67MB | 95/3558 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3209/3558 | `██████████░░░░░ 71%` |
| 4 | `runtime.mallocgc` | 31.58MB | 3209/3558 | `█████████░░░░░░ 61%` |
| 5 | `database/sql.convertAssignRows` | 24.53MB | 120/3558 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3558 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 15.65MB | 2538/3558 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3558 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.73MB | 85/3558 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3558 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3558 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3558 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3558 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3558 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 62.02GB | 2770/3558 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.54GB | 2932/3558 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 54.98GB | 2786/3558 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 52.78GB | 2550/3558 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3558 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3558 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
