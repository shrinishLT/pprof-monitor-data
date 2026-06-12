# Overview: prod
*Last updated: 2026-06-12 19:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T19:56 (3496 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,988 | avg: 14,445 | max: 84,644 | trend: INCREASING (+3.36/hr))
```
▁▁▁▁▁▁▁▁▂▅▄▄▃▂▂▃▄▂▄▁▁▁▁▁▁▂▁▁▁▄▂▃▂▁▂▂▂▅▆▄▄▃▂▂▃▃▃▄▂▃▁▂▂▁▁▃▂▁▁▁▁▁▁▁▁▂▂▁▃▁▁▁▁▃▂▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▁▂▅▄█▇
```

**Heap InUse** (current: 338.0MB | avg: 238.5MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▂▂▁▂▁▁▄▄▃▅▅▂▂▃▅▄▄▂▂▂▂▁▃▃▂▅▂▃▂▃▄▃▃▂▄▆▅▅▃▃▃▃▅▃▃▄▃▄▄▃▃▄▃▃▃▂▃▂▄▂▁▂▃▂▄▂▃▁▃▂▂▃▃▂▁▂▂▄▂▃▄▂▄▂▂▂▁▂▁▂▄▅▇█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,988 | 18,212 | -224 | 14,445 | 84,644 | INCREASING (+3.36/hr) |
| Heap InUse | 338.0MB | 308.4MB | +29.6MB | 238.5MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 683.2MB | 686.4MB | -3.2MB | 2628.5MB | 6883.9MB | |
| Heap Objects | 1,469,836 | 1,173,490 | +296346 | 1,023,696 | 17,165,538 | |

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
| 2026-06-12 | 240 | 16,063 | 263.9MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.85MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.56MB |
| 4 | `runtime.mallocgc` | 9.6MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 9.04MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 8 | `bufio.NewReaderSize` | 8.03MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `net/http.(*Transport).dialConn` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 10.94GB |
| 2 | `fmt.Sprintf` | 7.77GB |
| 3 | `reflect.unsafe_NewArray` | 5.59GB |
| 4 | `jackskj/carta.getUniqueId` | 5.2GB |
| 5 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.13GB |
| 6 | `reflect.growslice` | 5.09GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 4.97GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 4.97GB |
| 9 | `reflect.unsafe_New` | 4.33GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.16GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 800.72MB | 790.66MB | 595.55MB | 0B |
| `evaluation.mergeMetadata` | 414.10MB | 407.10MB | 308.98MB | 0B |
| `local.(*Client).EvaluateV2` | 1.21GB | 1.19GB | 922.59MB | 0B |
| `local.topologicalSort` | 178.79MB | 176.76MB | 133.93MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.11GB | 1.10GB | 852.29MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 202.49MB | 197.91MB | 142.86MB | 0B |
| `localEvaluation.getMapOfValue` | 1.11GB | 1.10GB | 852.29MB | 0B |
| `utils.ParseFeatureFlag` | 1.12GB | 1.10GB | 855.70MB | 512.56kB |

**Total FF alloc (current snapshot):** 6.11GB  |  **24h avg:** 4.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.6MB | 68/3496 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.12MB | 94/3496 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3147/3496 | `██████████░░░░░ 69%` |
| 4 | `runtime.mallocgc` | 31.93MB | 3147/3496 | `█████████░░░░░░ 60%` |
| 5 | `database/sql.convertAssignRows` | 24.89MB | 118/3496 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3496 | `█████░░░░░░░░░░ 34%` |
| 7 | `bytes.growSlice` | 15.64MB | 2486/3496 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3496 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*Transport).dialConn` | 13.9MB | 82/3496 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3496 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3496 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3496 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3496 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3496 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 63.26GB | 2708/3496 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.56GB | 2870/3496 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.06GB | 2724/3496 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 53.92GB | 2488/3496 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3496 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3496 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
