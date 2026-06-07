# Overview: prod
*Last updated: 2026-06-07 10:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T10:05 (1939 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,012 | avg: 12,980 | max: 84,644 | trend: INCREASING (+3.39/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▄█
```

**Heap InUse** (current: 282.8MB | avg: 190.1MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▃▂▁▂▁▁▁▂▃▃▃▃▃▁▂▂▂▃▂▂▁▃▂▂▃▃▁▁▂▃▁▁▁▃▂▄▆▂▄▄▅▃▂▂▂▃▅▃▄▄▄▄▅▃▃▃▃▃▅▃▃▁▂▃▃▃▂▂▄▂▄▂▄▂▂▂▃▂▂▂▁▁▄▃▄▃▂▃▁▆▄▅▃▅▆█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,012 | 17,941 | +3071 | 12,980 | 84,644 | INCREASING (+3.39/hr) |
| Heap InUse | 282.8MB | 244.9MB | +37.9MB | 190.1MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 833.9MB | 845.7MB | -11.8MB | 2228.8MB | 6883.9MB | |
| Heap Objects | 956,868 | 1,067,886 | -111018 | 861,906 | 17,165,538 | |

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
| 2026-06-07 | 122 | 14,469 | 162.0MB | 282.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 26.65MB |
| 3 | `runtime.mallocgc` | 15.6MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.57MB |
| 5 | `bufio.NewWriterSize` | 12.55MB |
| 6 | `bufio.NewReaderSize` | 10.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 10 | `reflect.growslice` | 4.58MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 28.58GB |
| 2 | `reflect.growslice` | 19.85GB |
| 3 | `jackskj/carta.getUniqueId` | 16.19GB |
| 4 | `reflect.unsafe_New` | 14.99GB |
| 5 | `reflect.unsafe_NewArray` | 14.51GB |
| 6 | `fmt.(*buffer).writeString` | 12.45GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 11.08GB |
| 8 | `carta/value.NewCell` | 10.5GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.85GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 769.35MB | 763.21MB | 671.69MB | 0B |
| `evaluation.mergeMetadata` | 398.10MB | 395.10MB | 349.60MB | 0B |
| `local.(*Client).EvaluateV2` | 1.14GB | 1.13GB | 1021.69MB | 0B |
| `local.topologicalSort` | 154.84MB | 154.33MB | 140.64MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.16GB | 1.15GB | 1.01GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 93.52MB | 93.52MB | 90.00MB | 0B |
| `localEvaluation.getMapOfValue` | 1.16GB | 1.15GB | 1.01GB | 0B |
| `utils.ParseFeatureFlag` | 1.17GB | 1.16GB | 1.01GB | 0B |

**Total FF alloc (current snapshot):** 6.01GB  |  **24h avg:** 5.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1939 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1939 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1590/1939 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1939 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1939 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.57MB | 1590/1939 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.4MB | 1169/1939 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1939 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1939 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/1939 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1939 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1939 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1939 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1939 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1939 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1939 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1939 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1939 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1939 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.36GB | 456/1939 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
