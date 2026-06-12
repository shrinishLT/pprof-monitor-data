# Overview: prod
*Last updated: 2026-06-13 01:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T01:15 (3560 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 26,275 | avg: 14,483 | max: 84,644 | trend: INCREASING (+3.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆▅▆▅▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▄▅
```

**Heap InUse** (current: 599.3MB | avg: 238.7MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆█▄▄▅▃▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▄▅▅
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 31%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 26,275 | 23,881 | +2394 | 14,483 | 84,644 | INCREASING (+3.31/hr) |
| Heap InUse | 599.3MB | 581.6MB | +17.7MB | 238.7MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1157.5MB | 1152.4MB | +5.1MB | 2598.0MB | 6883.9MB | |
| Heap Objects | 2,365,225 | 3,181,790 | -816565 | 1,026,443 | 17,165,538 | |

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
| 2026-06-13 | 16 | 16,574 | 267.2MB | 599.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 64.85MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewReaderSize` | 29.13MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 27.63MB |
| 5 | `bufio.NewWriterSize` | 24.09MB |
| 6 | `runtime.mallocgc` | 18.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 10.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 9.01MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 18.23GB |
| 2 | `fmt.Sprintf` | 12.31GB |
| 3 | `reflect.unsafe_NewArray` | 9.3GB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.2GB |
| 5 | `jackskj/carta.getUniqueId` | 9.15GB |
| 6 | `reflect.growslice` | 9.04GB |
| 7 | `reflect.unsafe_New` | 7.97GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.59GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 7.24GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.17GB | 1.16GB | 1.04GB | 0B |
| `evaluation.mergeMetadata` | 613.15MB | 605.15MB | 542.72MB | 0B |
| `local.(*Client).EvaluateV2` | 1.80GB | 1.78GB | 1.60GB | 0B |
| `local.topologicalSort` | 262.25MB | 258.71MB | 234.08MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.69GB | 1.67GB | 1.48GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 276.18MB | 272.66MB | 258.54MB | 0B |
| `localEvaluation.getMapOfValue` | 1.69GB | 1.67GB | 1.48GB | 0B |
| `utils.ParseFeatureFlag` | 1.69GB | 1.67GB | 1.48GB | 0B |

**Total FF alloc (current snapshot):** 9.16GB  |  **24h avg:** 8.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.24MB | 70/3560 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.67MB | 95/3560 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3211/3560 | `██████████░░░░░ 71%` |
| 4 | `runtime.mallocgc` | 31.57MB | 3211/3560 | `█████████░░░░░░ 61%` |
| 5 | `database/sql.convertAssignRows` | 24.53MB | 120/3560 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3560 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 15.69MB | 2540/3560 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3560 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.73MB | 85/3560 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3560 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3560 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3560 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3560 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3560 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 61.98GB | 2772/3560 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.51GB | 2934/3560 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 54.95GB | 2788/3560 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 52.74GB | 2552/3560 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3560 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3560 | `█████░░░░░░░░░░ 38%` |

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
