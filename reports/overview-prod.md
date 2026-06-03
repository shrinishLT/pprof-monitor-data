# Overview: prod
*Last updated: 2026-06-04 02:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:30 (985 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,277 | avg: 10,123 | max: 84,644 | trend: decreasing (-38.26/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄
```

**Heap InUse** (current: 169.8MB | avg: 148.7MB | max: 1896.6MB | trend: decreasing (-0.58MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅▃▃▃▃▃▃▄▄▄▅▄▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,277 | 16,058 | -1781 | 10,123 | 84,644 | decreasing (-38.26/hr) |
| Heap InUse | 169.8MB | 236.7MB | -66.9MB | 148.7MB | 1896.6MB | decreasing (-0.58MB/hr) |
| Heap Sys | 861.8MB | 861.2MB | +0.6MB | 2549.1MB | 6883.9MB | |
| Heap Objects | 886,394 | 804,344 | +82050 | 635,681 | 8,100,802 | |

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
| 2026-06-04 | 31 | 15,483 | 211.3MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.13MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bytes.growSlice` | 4.52MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 8 | `bufio.NewWriterSize` | 2.51MB |
| 9 | `reflect.unsafe_NewArray` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 2.42GB |
| 2 | `fmt.Sprintf` | 2.34GB |
| 3 | `jackskj/carta.getUniqueId` | 2.22GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 5 | `reflect.unsafe_New` | 1.99GB |
| 6 | `fmt.(*buffer).writeString` | 1.52GB |
| 7 | `segmentio/kafka-go.makePartitions` | 1.51GB |
| 8 | `carta/value.NewCell` | 1.45GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.31GB |
| 10 | `strconv.appendQuotedWith` | 1.16GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 70.66MB | 70.66MB | 67.76MB | 0B |
| `evaluation.mergeMetadata` | 36.01MB | 36.01MB | 34.88MB | 0B |
| `local.(*Client).EvaluateV2` | 112.38MB | 112.38MB | 103.13MB | 0B |
| `local.topologicalSort` | 20.26MB | 20.26MB | 17.57MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 104.81MB | 104.81MB | 91.78MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 13.23MB | 13.23MB | 18.80MB | 0B |
| `localEvaluation.getMapOfValue` | 104.81MB | 104.81MB | 91.78MB | 0B |
| `utils.ParseFeatureFlag` | 104.81MB | 104.81MB | 92.00MB | 0B |

**Total FF alloc (current snapshot):** 566.96MB  |  **24h avg:** 517.70MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/985 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/985 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 636/985 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/985 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.71MB | 636/985 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.32MB | 445/985 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/985 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/985 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/985 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 629/985 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/985 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/985 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/985 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/985 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.44GB | 613/985 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/985 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/985 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.46GB | 560/985 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.7GB | 303/985 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.01GB | 418/985 | `█░░░░░░░░░░░░░░ 10%` |

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
