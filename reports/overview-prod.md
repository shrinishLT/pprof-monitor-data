# Overview: prod
*Last updated: 2026-06-10 15:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T15:36 (2868 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,042 | avg: 14,089 | max: 84,644 | trend: INCREASING (+4.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 262.5MB | avg: 227.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,042 | 14,778 | +264 | 14,089 | 84,644 | INCREASING (+4.23/hr) |
| Heap InUse | 262.5MB | 307.3MB | -44.8MB | 227.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3337.4MB | 3337.2MB | +0.2MB | 2567.7MB | 6883.9MB | |
| Heap Objects | 1,113,192 | 1,656,960 | -543768 | 984,901 | 17,165,538 | |

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
| 2026-06-10 | 187 | 17,132 | 319.6MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 30.82MB |
| 4 | `database/sql.convertAssignRows` | 28.0MB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 25.49MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.07MB |
| 9 | `bufio.NewWriterSize` | 4.03MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 137.93GB |
| 2 | `segmentio/kafka-go.makePartitions` | 134.55GB |
| 3 | `jackskj/carta.getUniqueId` | 123.21GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.68GB |
| 5 | `reflect.unsafe_New` | 109.07GB |
| 6 | `fmt.Sprintf` | 93.05GB |
| 7 | `fmt.(*buffer).writeString` | 87.06GB |
| 8 | `carta/value.NewCell` | 78.01GB |
| 9 | `reflect.unsafe_NewArray` | 68.78GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.08GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.82GB | 6.81GB | 6.59GB | 0B |
| `evaluation.mergeMetadata` | 3.58GB | 3.57GB | 3.46GB | 0B |
| `local.(*Client).EvaluateV2` | 10.39GB | 10.38GB | 10.05GB | 0B |
| `local.topologicalSort` | 1.45GB | 1.44GB | 1.40GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.94GB | 9.93GB | 9.62GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.40GB | 1.40GB | 1.35GB | 0B |
| `localEvaluation.getMapOfValue` | 9.94GB | 9.93GB | 9.62GB | 0B |
| `utils.ParseFeatureFlag` | 9.96GB | 9.95GB | 9.63GB | 0B |

**Total FF alloc (current snapshot):** 53.48GB  |  **24h avg:** 51.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 50/2868 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 55.14MB | 79/2868 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2519/2868 | `███████░░░░░░░░ 53%` |
| 4 | `runtime.mallocgc` | 28.94MB | 2519/2868 | `██████░░░░░░░░░ 41%` |
| 5 | `database/sql.convertAssignRows` | 28.63MB | 100/2868 | `██████░░░░░░░░░ 41%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2868 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.88MB | 1930/2868 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2868 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2868 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2868 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2868 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2868 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2868 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2868 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 49.97GB | 1385/2868 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2868 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 40.73GB | 2242/2868 | `████░░░░░░░░░░░ 32%` |
| 8 | `reflect.growslice` | 39.62GB | 2080/2868 | `████░░░░░░░░░░░ 31%` |
| 9 | `jackskj/carta.getUniqueId` | 34.5GB | 2096/2868 | `████░░░░░░░░░░░ 27%` |
| 10 | `reflect.unsafe_New` | 34.0GB | 1860/2868 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
