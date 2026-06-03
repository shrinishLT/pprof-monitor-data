# Overview: prod
*Last updated: 2026-06-04 02:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:50 (989 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,019 | avg: 10,143 | max: 84,644 | trend: decreasing (-37.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅
```

**Heap InUse** (current: 219.9MB | avg: 149.0MB | max: 1896.6MB | trend: decreasing (-0.57MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅▃▃▃▃▃▃▄▄▄▅▄▃▄▄▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,019 | 15,205 | -186 | 10,143 | 84,644 | decreasing (-37.54/hr) |
| Heap InUse | 219.9MB | 201.6MB | +18.3MB | 149.0MB | 1896.6MB | decreasing (-0.57MB/hr) |
| Heap Sys | 860.2MB | 862.6MB | -2.4MB | 2542.3MB | 6883.9MB | |
| Heap Objects | 1,136,037 | 763,304 | +372733 | 637,389 | 8,100,802 | |

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
| 2026-06-04 | 35 | 15,458 | 212.7MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.13MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 1.51MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 2.73GB |
| 2 | `reflect.growslice` | 2.55GB |
| 3 | `jackskj/carta.getUniqueId` | 2.48GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 5 | `reflect.unsafe_New` | 2.15GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.93GB |
| 7 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.6GB |
| 8 | `fmt.(*buffer).writeString` | 1.56GB |
| 9 | `carta/value.NewCell` | 1.54GB |
| 10 | `strconv.appendQuotedWith` | 1.37GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 85.87MB | 82.35MB | 68.96MB | 0B |
| `evaluation.mergeMetadata` | 42.01MB | 40.01MB | 35.35MB | 0B |
| `local.(*Client).EvaluateV2` | 136.42MB | 131.82MB | 105.53MB | 0B |
| `local.topologicalSort` | 23.82MB | 23.82MB | 18.10MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 128.85MB | 124.77MB | 94.54MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 15.27MB | 14.23MB | 18.37MB | 0B |
| `localEvaluation.getMapOfValue` | 128.85MB | 124.77MB | 94.54MB | 0B |
| `utils.ParseFeatureFlag` | 128.85MB | 124.77MB | 94.74MB | 0B |

**Total FF alloc (current snapshot):** 689.92MB  |  **24h avg:** 530.14MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/989 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/989 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 640/989 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/989 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.67MB | 640/989 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.29MB | 448/989 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/989 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/989 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/989 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 633/989 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/989 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/989 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/989 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/989 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.16GB | 617/989 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/989 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/989 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.46GB | 560/989 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.54GB | 307/989 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.9GB | 422/989 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.3x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.2x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
