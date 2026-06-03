# Overview: prod
*Last updated: 2026-06-04 01:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T01:55 (978 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,356 | avg: 10,081 | max: 84,644 | trend: decreasing (-39.59/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅
```

**Heap InUse** (current: 190.4MB | avg: 148.1MB | max: 1896.6MB | trend: decreasing (-0.60MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅▃▃▃▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,356 | 14,497 | +859 | 10,081 | 84,644 | decreasing (-39.59/hr) |
| Heap InUse | 190.4MB | 195.9MB | -5.5MB | 148.1MB | 1896.6MB | decreasing (-0.60MB/hr) |
| Heap Sys | 861.9MB | 864.8MB | -2.9MB | 2561.2MB | 6883.9MB | |
| Heap Objects | 681,981 | 1,069,024 | -387043 | 633,142 | 8,100,802 | |

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
| 2026-06-04 | 24 | 15,361 | 202.7MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.13MB |
| 3 | `bytes.growSlice` | 11.56MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 2.51MB |
| 7 | `bufio.NewWriterSize` | 2.51MB |
| 8 | `reflect.growslice` | 2.33MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_New` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 2 | `fmt.Sprintf` | 1.03GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 890.1MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 870.95MB |
| 5 | `segmentio/kafka-go.makePartitions` | 855.33MB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 753.79MB |
| 7 | `reflect.growslice` | 748.86MB |
| 8 | `jackskj/carta.getUniqueId` | 722.13MB |
| 9 | `reflect.unsafe_New` | 604.77MB |
| 10 | `strconv.appendQuotedWith` | 524.15MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 49.39MB | 46.86MB | 68.79MB | 0B |
| `evaluation.mergeMetadata` | 25.01MB | 23.51MB | 35.52MB | 0B |
| `local.(*Client).EvaluateV2` | 76.68MB | 71.53MB | 103.93MB | 0B |
| `local.topologicalSort` | 13.66MB | 12.66MB | 17.49MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 74.73MB | 69.08MB | 91.40MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 7.08MB | 7.08MB | 20.47MB | 0B |
| `localEvaluation.getMapOfValue` | 74.73MB | 69.08MB | 91.40MB | 0B |
| `utils.ParseFeatureFlag` | 74.73MB | 69.08MB | 91.67MB | 0B |

**Total FF alloc (current snapshot):** 396.00MB  |  **24h avg:** 520.67MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/978 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/978 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 629/978 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/978 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.8MB | 629/978 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.31MB | 438/978 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/978 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/978 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/978 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 622/978 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/978 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/978 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/978 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/978 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.94GB | 606/978 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/978 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/978 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.49GB | 559/978 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.0GB | 296/978 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.21GB | 411/978 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.2x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
