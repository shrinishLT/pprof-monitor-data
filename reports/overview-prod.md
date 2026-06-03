# Overview: prod
*Last updated: 2026-06-04 03:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T03:55 (1002 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,781 | avg: 10,211 | max: 84,644 | trend: decreasing (-35.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅
```

**Heap InUse** (current: 154.1MB | avg: 152.4MB | max: 2823.8MB | trend: decreasing (-0.51MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,781 | 14,763 | +18 | 10,211 | 84,644 | decreasing (-35.31/hr) |
| Heap InUse | 154.1MB | 173.3MB | -19.2MB | 152.4MB | 2823.8MB | decreasing (-0.51MB/hr) |
| Heap Sys | 4529.0MB | 4527.8MB | +1.2MB | 2568.0MB | 6883.9MB | |
| Heap Objects | 280,530 | 567,274 | -286744 | 653,636 | 14,090,816 | |

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
| 2026-06-04 | 48 | 15,421 | 266.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.13MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bytes.growSlice` | 7.09MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.06MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.38GB |
| 2 | `fmt.Sprintf` | 3.76GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.32GB |
| 4 | `reflect.growslice` | 3.25GB |
| 5 | `jackskj/carta.getUniqueId` | 3.25GB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.24GB |
| 7 | `reflect.unsafe_New` | 2.74GB |
| 8 | `fmt.(*buffer).writeString` | 1.99GB |
| 9 | `carta/value.NewCell` | 1.97GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.88GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 146.29MB | 141.09MB | 77.65MB | 0B |
| `evaluation.mergeMetadata` | 78.02MB | 75.52MB | 40.34MB | 0B |
| `local.(*Client).EvaluateV2` | 224.84MB | 215.46MB | 119.39MB | 0B |
| `local.topologicalSort` | 32.96MB | 31.94MB | 20.16MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 218.82MB | 209.49MB | 111.75MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 19.32MB | 18.78MB | 15.23MB | 0B |
| `localEvaluation.getMapOfValue` | 218.82MB | 209.49MB | 111.75MB | 0B |
| `utils.ParseFeatureFlag` | 218.82MB | 209.49MB | 111.90MB | 0B |

**Total FF alloc (current snapshot):** 1.13GB  |  **24h avg:** 608.18MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 67.61MB | 27/1002 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1002 | `█████████████░░ 93%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 653/1002 | `████████░░░░░░░ 54%` |
| 4 | `database/sql.convertAssignRows` | 33.77MB | 35/1002 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.52MB | 653/1002 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1002 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 13.19MB | 460/1002 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 11.31MB | 8/1002 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 17/1002 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1002 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1002 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1002 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1002 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1002 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 44.4GB | 630/1002 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1002 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1002 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.07GB | 573/1002 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.08GB | 320/1002 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.6GB | 435/1002 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.3x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
