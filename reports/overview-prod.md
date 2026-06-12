# Overview: prod
*Last updated: 2026-06-12 12:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T12:45 (3410 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,469 | avg: 14,429 | max: 84,644 | trend: INCREASING (+3.56/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 235.2MB | avg: 239.6MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,469 | 15,290 | +1179 | 14,429 | 84,644 | INCREASING (+3.56/hr) |
| Heap InUse | 235.2MB | 226.4MB | +8.8MB | 239.6MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 342.6MB | 306.1MB | +36.5MB | 2678.8MB | 6883.9MB | |
| Heap Objects | 981,888 | 1,432,874 | -450986 | 1,028,328 | 17,165,538 | |

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
| 2026-06-12 | 154 | 16,613 | 303.8MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 15.61MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `runtime.mallocgc` | 7.5MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.66MB |
| 7 | `bufio.NewWriterSize` | 6.04MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `bufio.NewReaderSize` | 3.51MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.1GB |
| 2 | `jackskj/carta.getUniqueId` | 1.01GB |
| 3 | `reflect.growslice` | 989.19MB |
| 4 | `reflect.unsafe_New` | 840.36MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 686.76MB |
| 6 | `carta/value.NewCell` | 616.05MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 587.33MB |
| 8 | `reflect.unsafe_NewArray` | 582.0MB |
| 9 | `fmt.Sprintf` | 538.27MB |
| 10 | `fmt.(*buffer).writeString` | 470.84MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 69.01MB | 55.79MB | 8.19GB | 0B |
| `evaluation.mergeMetadata` | 38.01MB | 30.51MB | 4.27GB | 0B |
| `local.(*Client).EvaluateV2` | 104.10MB | 80.61MB | 12.47GB | 0B |
| `local.topologicalSort` | 18.73MB | 11.63MB | 1.74GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 91.82MB | 75.49MB | 11.93GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 20.44MB | 12.26MB | 1.69GB | 0B |
| `localEvaluation.getMapOfValue` | 91.82MB | 75.49MB | 11.93GB | 0B |
| `utils.ParseFeatureFlag` | 92.32MB | 75.49MB | 11.95GB | 512.56kB |

**Total FF alloc (current snapshot):** 526.24MB  |  **24h avg:** 64.19GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3410 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3410 | `█████████████░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3061/3410 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.6MB | 3061/3410 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3410 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3410 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.89MB | 2405/3410 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3410 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3410 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3410 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3410 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3410 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3410 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.22GB | 1916/3410 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 65.19GB | 2622/3410 | `███████░░░░░░░░ 52%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.3GB | 2784/3410 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.74GB | 2638/3410 | `██████░░░░░░░░░ 46%` |
| 8 | `reflect.unsafe_New` | 55.72GB | 2402/3410 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3410 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.56GB | 2141/3410 | `█████░░░░░░░░░░ 39%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
