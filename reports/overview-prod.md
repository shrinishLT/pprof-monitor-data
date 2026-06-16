# Overview: prod
*Last updated: 2026-06-16 20:12 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T20:12 (4647 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 23,161 | avg: 14,862 | max: 84,644 | trend: INCREASING (+2.23/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▂▂▁▁▁▁▂▆█
```

**Heap InUse** (current: 467.6MB | avg: 245.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▂▃▁▁▂▁▃▂▁▂▃▂▂▁▁▂▂▃▂▃▂▁▁▁▁▁▁▂▂▁▂▁▂▁▂▂▁▁▁▃▂▃▂▂▂▁▁▁▂▂▁▁▁▁▂▂▂▂▂▂▂▁▂▂▁▂▂▁▂▂▂▄▂▂▁▁▁▂▂▂▂▂▂▂▁▂▂▂▁▁▂▂▃█▇
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 27%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 23,161 | 21,780 | +1381 | 14,862 | 84,644 | INCREASING (+2.23/hr) |
| Heap InUse | 467.6MB | 508.0MB | -40.4MB | 245.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 981.6MB | 986.4MB | -4.8MB | 2479.5MB | 6883.9MB | |
| Heap Objects | 2,009,853 | 2,685,936 | -676083 | 1,051,979 | 17,165,538 | |

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
| 2026-06-16 | 241 | 16,176 | 253.7MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 56.97MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewReaderSize` | 27.6MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 24.11MB |
| 5 | `bufio.NewWriterSize` | 23.09MB |
| 6 | `runtime.mallocgc` | 12.51MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 10.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 12.01GB |
| 2 | `fmt.Sprintf` | 8.38GB |
| 3 | `jackskj/carta.getUniqueId` | 6.93GB |
| 4 | `reflect.growslice` | 6.81GB |
| 5 | `reflect.unsafe_NewArray` | 6.35GB |
| 6 | `reflect.unsafe_New` | 5.82GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.66GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 5.41GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.65GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 998.12MB | 988.96MB | 742.43MB | 0B |
| `evaluation.mergeMetadata` | 512.12MB | 506.62MB | 380.66MB | 0B |
| `local.(*Client).EvaluateV2` | 1.48GB | 1.46GB | 1.10GB | 0B |
| `local.topologicalSort` | 198.87MB | 197.85MB | 149.79MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.39GB | 1.37GB | 1.04GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 244.49MB | 242.91MB | 181.01MB | 0B |
| `localEvaluation.getMapOfValue` | 1.39GB | 1.37GB | 1.04GB | 0B |
| `utils.ParseFeatureFlag` | 1.39GB | 1.37GB | 1.04GB | 0B |

**Total FF alloc (current snapshot):** 7.54GB  |  **24h avg:** 5.64GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4647 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4298/4647 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.6MB | 133/4647 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.87MB | 4298/4647 | `████████████░░░ 80%` |
| 5 | `database/sql.convertAssignRows` | 20.45MB | 155/4647 | `███████░░░░░░░░ 53%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4647 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.69MB | 3397/4647 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4647 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4647 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4647 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4647 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4647 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4647 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4647 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.33GB | 3859/4647 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.19GB | 4021/4647 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.58GB | 3875/4647 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 52.88GB | 3639/4647 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4647 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4647 | `█████░░░░░░░░░░ 37%` |

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
