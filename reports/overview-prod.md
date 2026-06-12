# Overview: prod
*Last updated: 2026-06-12 22:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T22:45 (3530 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 30,099 | avg: 14,467 | max: 84,644 | trend: INCREASING (+3.34/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆▅▆
```

**Heap InUse** (current: 523.0MB | avg: 238.5MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆█▄▄
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 35%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 30,099 | 25,650 | +4449 | 14,467 | 84,644 | INCREASING (+3.34/hr) |
| Heap InUse | 523.0MB | 435.4MB | +87.6MB | 238.5MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1021.8MB | 1019.0MB | +2.8MB | 2610.1MB | 6883.9MB | |
| Heap Objects | 1,297,226 | 1,621,255 | -324029 | 1,024,441 | 17,165,538 | |

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
| 2026-06-12 | 274 | 16,146 | 261.1MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 87.03MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 42.2MB |
| 3 | `bufio.NewReaderSize` | 36.64MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `bufio.NewWriterSize` | 30.62MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 19.52MB |
| 7 | `runtime.mallocgc` | 18.22MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `crypto/tls.Client` | 8.51MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 14.82GB |
| 2 | `fmt.Sprintf` | 11.22GB |
| 3 | `reflect.growslice` | 8.52GB |
| 4 | `jackskj/carta.getUniqueId` | 8.51GB |
| 5 | `reflect.unsafe_NewArray` | 7.54GB |
| 6 | `reflect.unsafe_New` | 7.4GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.97GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.83GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.78GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 5.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.00GB | 1020.46MB | 875.41MB | 0B |
| `evaluation.mergeMetadata` | 525.13MB | 522.63MB | 451.03MB | 0B |
| `local.(*Client).EvaluateV2` | 1.55GB | 1.54GB | 1.32GB | 0B |
| `local.topologicalSort` | 227.83MB | 226.32MB | 195.23MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.43GB | 1.42GB | 1.21GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 252.74MB | 252.24MB | 221.55MB | 0B |
| `localEvaluation.getMapOfValue` | 1.43GB | 1.42GB | 1.21GB | 0B |
| `utils.ParseFeatureFlag` | 1.43GB | 1.42GB | 1.22GB | 0B |

**Total FF alloc (current snapshot):** 7.82GB  |  **24h avg:** 6.67GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.9MB | 69/3530 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.67MB | 95/3530 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3181/3530 | `██████████░░░░░ 70%` |
| 4 | `runtime.mallocgc` | 31.7MB | 3181/3530 | `█████████░░░░░░ 61%` |
| 5 | `database/sql.convertAssignRows` | 24.7MB | 119/3530 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3530 | `█████░░░░░░░░░░ 34%` |
| 7 | `bytes.growSlice` | 15.67MB | 2515/3530 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3530 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.81MB | 84/3530 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3530 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3530 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3530 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3530 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3530 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 62.56GB | 2742/3530 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.98GB | 2904/3530 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.45GB | 2758/3530 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 53.28GB | 2522/3530 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3530 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3530 | `█████░░░░░░░░░░ 38%` |

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
