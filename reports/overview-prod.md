# Overview: prod
*Last updated: 2026-06-13 03:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T03:25 (3586 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,757 | avg: 14,524 | max: 84,644 | trend: INCREASING (+3.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▅▃▄▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▃▂▂
```

**Heap InUse** (current: 470.5MB | avg: 239.6MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▂▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▅▃▃▄▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▄▃▃▃▄▂▂▁▁▁▁▁▁▂▁▁▁▁▁▂▁█▃▄▄▂▃
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 25%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,757 | 22,344 | -587 | 14,524 | 84,644 | INCREASING (+3.37/hr) |
| Heap InUse | 470.5MB | 331.0MB | +139.5MB | 239.6MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1385.1MB | 1294.8MB | +90.3MB | 2587.8MB | 6883.9MB | |
| Heap Objects | 1,620,903 | 752,986 | +867917 | 1,029,528 | 17,165,538 | |

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
| 2026-06-13 | 42 | 18,770 | 323.5MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 45.24MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 23.22MB |
| 4 | `bufio.NewReaderSize` | 19.6MB |
| 5 | `bufio.NewWriterSize` | 18.08MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.58MB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 5.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 21.19GB |
| 2 | `fmt.Sprintf` | 14.8GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 14.14GB |
| 4 | `jackskj/carta.getUniqueId` | 12.23GB |
| 5 | `reflect.growslice` | 12.18GB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 11.64GB |
| 7 | `reflect.unsafe_New` | 10.8GB |
| 8 | `reflect.unsafe_NewArray` | 10.76GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 9.27GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 7.82GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.31GB | 1.31GB | 1.19GB | 0B |
| `evaluation.mergeMetadata` | 690.17MB | 688.67MB | 620.64MB | 0B |
| `local.(*Client).EvaluateV2` | 2.02GB | 2.01GB | 1.82GB | 0B |
| `local.topologicalSort` | 292.61MB | 291.08MB | 263.95MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.90GB | 1.89GB | 1.70GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 307.89MB | 306.81MB | 283.25MB | 0B |
| `localEvaluation.getMapOfValue` | 1.90GB | 1.89GB | 1.70GB | 0B |
| `utils.ParseFeatureFlag` | 1.90GB | 1.90GB | 1.71GB | 0B |

**Total FF alloc (current snapshot):** 10.29GB  |  **24h avg:** 9.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.24MB | 70/3586 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.67MB | 95/3586 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3237/3586 | `██████████░░░░░ 71%` |
| 4 | `runtime.mallocgc` | 31.47MB | 3237/3586 | `█████████░░░░░░ 61%` |
| 5 | `database/sql.convertAssignRows` | 24.53MB | 120/3586 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3586 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 15.88MB | 2564/3586 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3586 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.54MB | 89/3586 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3586 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3586 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3586 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3586 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3586 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 61.51GB | 2798/3586 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.14GB | 2960/3586 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.54GB | 2814/3586 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 52.31GB | 2578/3586 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3586 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3586 | `█████░░░░░░░░░░ 38%` |

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
