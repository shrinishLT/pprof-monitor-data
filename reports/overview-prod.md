# Overview: prod
*Last updated: 2026-06-07 10:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T10:01 (1938 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,941 | avg: 12,976 | max: 84,644 | trend: INCREASING (+3.37/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▃▂▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▃▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▃▂▃▂▃█
```

**Heap InUse** (current: 244.9MB | avg: 190.1MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▃▄▂▁▃▁▁▁▃▃▄▃▃▄▂▂▃▂▃▂▂▂▄▃▃▄▄▂▁▃▃▁▁▁▄▂▅█▂▅▄▆▃▂▂▂▄▆▄▅▅▅▄▆▄▃▄▄▄▅▄▄▁▂▃▄▄▃▃▄▂▅▃▄▃▂▃▃▂▂▂▂▂▄▃▄▄▂▄▁▇▅▇▄▆▇
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,941 | 15,250 | +2691 | 12,976 | 84,644 | INCREASING (+3.37/hr) |
| Heap InUse | 244.9MB | 214.2MB | +30.7MB | 190.1MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 845.7MB | 853.7MB | -8.0MB | 2229.5MB | 6883.9MB | |
| Heap Objects | 1,067,886 | 1,197,873 | -129987 | 861,857 | 17,165,538 | |

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
| 2026-06-07 | 121 | 14,415 | 161.0MB | 247.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 19.11MB |
| 3 | `runtime.mallocgc` | 12.08MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 5 | `bufio.NewWriterSize` | 9.54MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `bufio.NewReaderSize` | 7.53MB |
| 9 | `jackskj/carta.getUniqueId` | 4.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 28.49GB |
| 2 | `reflect.growslice` | 19.21GB |
| 3 | `jackskj/carta.getUniqueId` | 15.64GB |
| 4 | `reflect.unsafe_New` | 14.49GB |
| 5 | `reflect.unsafe_NewArray` | 14.47GB |
| 6 | `fmt.(*buffer).writeString` | 12.09GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 11.08GB |
| 8 | `carta/value.NewCell` | 10.14GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.7GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 763.21MB | 756.55MB | 667.48MB | 0B |
| `evaluation.mergeMetadata` | 395.10MB | 391.59MB | 347.51MB | 0B |
| `local.(*Client).EvaluateV2` | 1.13GB | 1.12GB | 1015.61MB | 0B |
| `local.topologicalSort` | 154.33MB | 152.81MB | 139.97MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.15GB | 1.14GB | 1.00GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 93.52MB | 93.52MB | 89.71MB | 0B |
| `localEvaluation.getMapOfValue` | 1.15GB | 1.14GB | 1.00GB | 0B |
| `utils.ParseFeatureFlag` | 1.16GB | 1.15GB | 1.00GB | 0B |

**Total FF alloc (current snapshot):** 5.97GB  |  **24h avg:** 5.22GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1938 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1938 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1589/1938 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1938 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1938 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.57MB | 1589/1938 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.39MB | 1168/1938 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1938 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1938 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/1938 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1938 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1938 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1938 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1938 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1938 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1938 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1938 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1938 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1938 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.36GB | 455/1938 | `█░░░░░░░░░░░░░░ 9%` |

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
