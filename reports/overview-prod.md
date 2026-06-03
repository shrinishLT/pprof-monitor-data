# Overview: prod
*Last updated: 2026-06-04 01:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T01:20 (971 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,184 | avg: 10,034 | max: 84,644 | trend: decreasing (-41.05/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇▆▇▇▆▆▆▆▇▆▆▆▆▆▆▆▇▆▆▆▆▆
```

**Heap InUse** (current: 112.4MB | avg: 147.3MB | max: 1896.6MB | trend: decreasing (-0.62MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▇▆▅▅▆▄▄▆▄█▆▃▃▃▅▄▄▅▅▅▅▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,184 | 14,535 | -351 | 10,034 | 84,644 | decreasing (-41.05/hr) |
| Heap InUse | 112.4MB | 187.8MB | -75.4MB | 147.3MB | 1896.6MB | decreasing (-0.62MB/hr) |
| Heap Sys | 894.4MB | 893.5MB | +0.9MB | 2573.5MB | 6883.9MB | |
| Heap Objects | 355,313 | 593,266 | -237953 | 630,257 | 8,100,802 | |

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
| 2026-06-04 | 17 | 14,820 | 181.1MB | 318.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.growslice` | 2.32MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `bytes.growSlice` | 1.63MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.14GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 854.83MB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 561.29MB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 474.01MB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 337.01MB |
| 6 | `database/sql.convertAssignRows` | 292.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 198.82MB |
| 8 | `fmt.Sprintf` | 110.89MB |
| 9 | `reflect.unsafe_NewArray` | 92.93MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 83.62MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 17.86MB | 13.82MB | 77.62MB | 0B |
| `evaluation.mergeMetadata` | 8.50MB | 6.50MB | 40.32MB | 0B |
| `local.(*Client).EvaluateV2` | 30.69MB | 25.12MB | 116.86MB | 0B |
| `local.topologicalSort` | 5.57MB | 5.57MB | 19.58MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 27.72MB | 23.66MB | 101.63MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 4.51MB | 3.00MB | 24.47MB | 0B |
| `localEvaluation.getMapOfValue` | 27.72MB | 23.66MB | 101.63MB | 0B |
| `utils.ParseFeatureFlag` | 27.72MB | 23.66MB | 101.98MB | 0B |

**Total FF alloc (current snapshot):** 150.29MB  |  **24h avg:** 584.09MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/971 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/971 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 622/971 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/971 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.89MB | 622/971 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.23MB | 431/971 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/971 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/971 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/971 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 615/971 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/971 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/971 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/971 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/971 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 46.45GB | 599/971 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/971 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/971 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.74GB | 552/971 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.35GB | 289/971 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.43GB | 404/971 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
