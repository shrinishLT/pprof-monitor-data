# Overview: prod
*Last updated: 2026-06-05 03:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T03:35 (1286 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,262 | avg: 11,595 | max: 84,644 | trend: decreasing (-6.82/hr))
```
▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂
```

**Heap InUse** (current: 211.0MB | avg: 177.3MB | max: 3154.1MB | trend: stable (-0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,262 | 14,737 | +525 | 11,595 | 84,644 | decreasing (-6.82/hr) |
| Heap InUse | 211.0MB | 215.1MB | -4.1MB | 177.3MB | 3154.1MB | stable (-0.06MB/hr) |
| Heap Sys | 3173.7MB | 3175.1MB | -1.4MB | 2664.1MB | 6883.9MB | |
| Heap Objects | 1,280,030 | 1,244,344 | +35686 | 779,833 | 17,165,538 | |

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
| 2026-06-05 | 44 | 14,841 | 263.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `bytes.growSlice` | 9.05MB |
| 4 | `runtime.mallocgc` | 6.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 7 | `bufio.NewReaderSize` | 4.54MB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 4.02MB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 3.74MB |
| 10 | `database/sql.convertAssignRows` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.13GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 3.25GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.48GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.13GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.04GB |
| 6 | `database/sql.convertAssignRows` | 1017.55MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 879.3MB |
| 8 | `reflect.unsafe_NewArray` | 793.96MB |
| 9 | `fmt.Sprintf` | 507.47MB |
| 10 | `reflect.MakeSlice` | 434.51MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 82.56MB | 69.44MB | 138.18MB | 0B |
| `evaluation.mergeMetadata` | 42.51MB | 35.51MB | 70.49MB | 0B |
| `local.(*Client).EvaluateV2` | 122.47MB | 106.27MB | 197.34MB | 0B |
| `local.topologicalSort` | 16.69MB | 15.17MB | 28.44MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 116.36MB | 99.64MB | 182.86MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 16.34MB | 15.84MB | 29.37MB | 0B |
| `localEvaluation.getMapOfValue` | 116.36MB | 99.64MB | 182.86MB | 0B |
| `utils.ParseFeatureFlag` | 116.86MB | 100.14MB | 182.97MB | 0B |

**Total FF alloc (current snapshot):** 630.17MB  |  **24h avg:** 1012.51MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 76.66MB | 28/1286 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.25MB | 44/1286 | `██████████████░ 98%` |
| 3 | `database/sql.convertAssignRows` | 37.16MB | 56/1286 | `███████░░░░░░░░ 48%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 937/1286 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 18.68MB | 937/1286 | `███░░░░░░░░░░░░ 24%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1286 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 14.67MB | 714/1286 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1286 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1286 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1286 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1286 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1286 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1286 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1286 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1286 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.86GB | 909/1286 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1286 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.0GB | 832/1286 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 10.2GB | 517/1286 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1286 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
