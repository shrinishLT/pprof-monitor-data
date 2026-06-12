# Overview: prod
*Last updated: 2026-06-12 22:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T22:50 (3531 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 25,819 | avg: 14,470 | max: 84,644 | trend: INCREASING (+3.34/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆▅▆▅
```

**Heap InUse** (current: 610.9MB | avg: 238.6MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▂▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆█▄▄▅
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 30%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 25,819 | 30,099 | -4280 | 14,470 | 84,644 | INCREASING (+3.34/hr) |
| Heap InUse | 610.9MB | 523.0MB | +87.9MB | 238.6MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1145.5MB | 1021.8MB | +123.7MB | 2609.7MB | 6883.9MB | |
| Heap Objects | 3,207,396 | 1,297,226 | +1910170 | 1,025,060 | 17,165,538 | |

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
| 2026-06-12 | 275 | 16,181 | 262.4MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 75.49MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 33.66MB |
| 4 | `bufio.NewReaderSize` | 31.62MB |
| 5 | `bufio.NewWriterSize` | 24.59MB |
| 6 | `runtime.mallocgc` | 18.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 14.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 10 | `net/http.(*Transport).dialConn` | 7.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 14.92GB |
| 2 | `fmt.Sprintf` | 11.33GB |
| 3 | `jackskj/carta.getUniqueId` | 8.59GB |
| 4 | `reflect.growslice` | 8.59GB |
| 5 | `reflect.unsafe_NewArray` | 7.6GB |
| 6 | `reflect.unsafe_New` | 7.47GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.97GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 6.05GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.83GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.78GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.01GB | 1.00GB | 882.71MB | 0B |
| `evaluation.mergeMetadata` | 528.13MB | 525.13MB | 454.57MB | 0B |
| `local.(*Client).EvaluateV2` | 1.55GB | 1.55GB | 1.33GB | 0B |
| `local.topologicalSort` | 229.35MB | 227.83MB | 196.81MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.43GB | 1.43GB | 1.22GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 253.28MB | 252.74MB | 223.42MB | 0B |
| `localEvaluation.getMapOfValue` | 1.43GB | 1.43GB | 1.22GB | 0B |
| `utils.ParseFeatureFlag` | 1.44GB | 1.43GB | 1.23GB | 0B |

**Total FF alloc (current snapshot):** 7.85GB  |  **24h avg:** 6.73GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.9MB | 69/3531 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.67MB | 95/3531 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3182/3531 | `██████████░░░░░ 70%` |
| 4 | `runtime.mallocgc` | 31.69MB | 3182/3531 | `█████████░░░░░░ 61%` |
| 5 | `database/sql.convertAssignRows` | 24.7MB | 119/3531 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3531 | `█████░░░░░░░░░░ 34%` |
| 7 | `bytes.growSlice` | 15.69MB | 2516/3531 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3531 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.73MB | 85/3531 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3531 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3531 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3531 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3531 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3531 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 62.54GB | 2743/3531 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.96GB | 2905/3531 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.44GB | 2759/3531 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 53.26GB | 2523/3531 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3531 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3531 | `█████░░░░░░░░░░ 38%` |

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
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
