# Overview: prod
*Last updated: 2026-06-16 20:07 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T20:07 (4646 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,780 | avg: 14,860 | max: 84,644 | trend: INCREASING (+2.23/hr))
```
▁▁▁▁▁▁▂▂▂▂▁▂▂▁▁▁▁▁▂▃▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▄▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▃▂▁▂▁▁▁▂▂▁▁▁▁▂█
```

**Heap InUse** (current: 508.0MB | avg: 245.2MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▂▃▁▁▂▁▃▂▁▂▃▂▂▁▁▂▂▃▂▃▂▁▁▁▁▁▁▂▂▁▂▁▂▁▂▂▁▁▁▃▂▃▂▂▂▁▁▁▂▂▁▁▁▁▂▂▂▂▂▂▂▁▂▂▁▂▂▁▂▂▂▄▂▂▁▁▁▂▂▂▂▂▂▂▁▂▂▂▁▁▂▂▃█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 25%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,780 | 15,830 | +5950 | 14,860 | 84,644 | INCREASING (+2.23/hr) |
| Heap InUse | 508.0MB | 243.1MB | +264.9MB | 245.2MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 986.4MB | 1005.7MB | -19.3MB | 2479.9MB | 6883.9MB | |
| Heap Objects | 2,685,936 | 1,369,651 | +1316285 | 1,051,773 | 17,165,538 | |

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
| 2026-06-16 | 240 | 16,147 | 252.8MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 42.67MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewReaderSize` | 19.57MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 19.09MB |
| 5 | `bufio.NewWriterSize` | 18.57MB |
| 6 | `runtime.mallocgc` | 12.51MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.51MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |
| 10 | `compress/flate.NewWriter` | 4.41MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 11.91GB |
| 2 | `fmt.Sprintf` | 8.08GB |
| 3 | `jackskj/carta.getUniqueId` | 6.81GB |
| 4 | `reflect.growslice` | 6.74GB |
| 5 | `reflect.unsafe_NewArray` | 6.3GB |
| 6 | `reflect.unsafe_New` | 5.74GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.66GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 5.41GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.65GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.33GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 988.96MB | 974.28MB | 731.78MB | 0B |
| `evaluation.mergeMetadata` | 506.62MB | 500.12MB | 375.23MB | 0B |
| `local.(*Client).EvaluateV2` | 1.46GB | 1.44GB | 1.09GB | 0B |
| `local.topologicalSort` | 197.85MB | 196.83MB | 147.70MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.37GB | 1.36GB | 1.02GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 242.91MB | 239.84MB | 178.26MB | 0B |
| `localEvaluation.getMapOfValue` | 1.37GB | 1.36GB | 1.02GB | 0B |
| `utils.ParseFeatureFlag` | 1.37GB | 1.36GB | 1.03GB | 0B |

**Total FF alloc (current snapshot):** 7.47GB  |  **24h avg:** 5.56GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4646 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4297/4646 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.6MB | 133/4646 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.88MB | 4297/4646 | `████████████░░░ 80%` |
| 5 | `database/sql.convertAssignRows` | 20.45MB | 155/4646 | `███████░░░░░░░░ 53%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4646 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.68MB | 3396/4646 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4646 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4646 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4646 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4646 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4646 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4646 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4646 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.34GB | 3858/4646 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.2GB | 4020/4646 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.59GB | 3874/4646 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 52.9GB | 3638/4646 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4646 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4646 | `█████░░░░░░░░░░ 37%` |

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
