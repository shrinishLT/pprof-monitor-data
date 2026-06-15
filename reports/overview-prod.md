# Overview: prod
*Last updated: 2026-06-15 06:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T06:10 (4195 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,268 | avg: 14,691 | max: 84,644 | trend: INCREASING (+2.50/hr))
```
▁▄▁▁▁▁▁▁▁▁▁▂▁▄▁▁▂▁▁▂▁▃▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▂▁▂▁▁▁▄▅▃▂▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▂▂▂▂▂▃▄▂▁▁▁▁▂▁▁▁▁▂▁▅▅▅█▆▁▁▁▁▁▃▅
```

**Heap InUse** (current: 264.7MB | avg: 241.9MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▃▄▃▄▅▁▄▁▃▄▂▂▃▄▃▁▃▂▂▄▂▅▂▃▄▂▁▄▂▄▂▄▁▄▂▄▄▁▄▃▁▅▂▂▃▆▆▁█▂▄▁▅▅▄▁▃▁▄▁▅▁▃▁▃▃▂▂▂▂▃▄▃▃▁▂▄▄▃▃▂▄▃▂▄▆▇▅▄▁▄▅▃▂▄▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,268 | 14,821 | +447 | 14,691 | 84,644 | INCREASING (+2.50/hr) |
| Heap InUse | 264.7MB | 231.5MB | +33.2MB | 241.9MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2411.1MB | 2411.7MB | -0.6MB | 2528.2MB | 6883.9MB | |
| Heap Objects | 952,556 | 725,360 | +227196 | 1,040,145 | 17,165,538 | |

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
| 2026-06-15 | 75 | 14,406 | 220.8MB | 323.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.55MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewReaderSize` | 4.02MB |
| 7 | `bufio.NewWriterSize` | 3.54MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 98.32GB |
| 2 | `reflect.growslice` | 91.89GB |
| 3 | `segmentio/kafka-go.makePartitions` | 90.64GB |
| 4 | `jackskj/carta.getUniqueId` | 82.26GB |
| 5 | `reflect.unsafe_New` | 72.17GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 70.51GB |
| 7 | `fmt.Sprintf` | 58.81GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 57.96GB |
| 9 | `fmt.(*buffer).writeString` | 56.9GB |
| 10 | `carta/value.NewCell` | 52.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.30GB | 3.29GB | 3.23GB | 0B |
| `evaluation.mergeMetadata` | 1.69GB | 1.69GB | 1.66GB | 0B |
| `local.(*Client).EvaluateV2` | 5.07GB | 5.06GB | 4.97GB | 0B |
| `local.topologicalSort` | 734.61MB | 733.10MB | 719.68MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.98GB | 4.97GB | 4.87GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 599.10MB | 599.10MB | 593.16MB | 0B |
| `localEvaluation.getMapOfValue` | 4.98GB | 4.97GB | 4.87GB | 0B |
| `utils.ParseFeatureFlag` | 4.99GB | 4.98GB | 4.88GB | 0B |

**Total FF alloc (current snapshot):** 26.31GB  |  **24h avg:** 25.75GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.86MB | 84/4195 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 39.14MB | 116/4195 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3846/4195 | `████████████░░░ 83%` |
| 4 | `runtime.mallocgc` | 31.29MB | 3846/4195 | `██████████░░░░░ 71%` |
| 5 | `database/sql.convertAssignRows` | 22.27MB | 135/4195 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4195 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.6MB | 2987/4195 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4195 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4195 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4195 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4195 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4195 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4195 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.97GB | 2384/4195 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 60.27GB | 3407/4195 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.26GB | 3569/4195 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.73GB | 3423/4195 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4195 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.67GB | 3187/4195 | `██████░░░░░░░░░ 40%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4195 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
