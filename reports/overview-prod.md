# Overview: prod
*Last updated: 2026-06-04 06:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T06:15 (1030 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,569 | avg: 10,362 | max: 84,644 | trend: decreasing (-30.80/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅▅▅▅▅▅▅▄▄▄▅▅▅
```

**Heap InUse** (current: 207.4MB | avg: 155.0MB | max: 2823.8MB | trend: stable (-0.44MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,569 | 14,857 | +712 | 10,362 | 84,644 | decreasing (-30.80/hr) |
| Heap InUse | 207.4MB | 347.2MB | -139.8MB | 155.0MB | 2823.8MB | stable (-0.44MB/hr) |
| Heap Sys | 2250.6MB | 2250.2MB | +0.4MB | 2547.4MB | 6883.9MB | |
| Heap Objects | 809,383 | 2,078,267 | -1268884 | 663,645 | 14,090,816 | |

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
| 2026-06-04 | 76 | 15,547 | 259.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 42.23MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 27.0MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 12.89MB |
| 5 | `runtime.mallocgc` | 12.6MB |
| 6 | `bytes.growSlice` | 10.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `bufio.NewWriterSize` | 5.03MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.87GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.34GB |
| 3 | `reflect.growslice` | 6.11GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.02GB |
| 5 | `jackskj/carta.getUniqueId` | 4.86GB |
| 6 | `reflect.unsafe_New` | 4.48GB |
| 7 | `fmt.(*buffer).writeString` | 3.6GB |
| 8 | `carta/value.NewCell` | 3.15GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 2.81GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.79GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 51.14MB | 47.08MB | 76.47MB | 0B |
| `evaluation.mergeMetadata` | 30.01MB | 27.51MB | 40.27MB | 0B |
| `local.(*Client).EvaluateV2` | 74.01MB | 66.80MB | 116.89MB | 0B |
| `local.topologicalSort` | 7.08MB | 6.57MB | 18.06MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 73.44MB | 69.30MB | 114.11MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 11.81MB | 8.74MB | 10.62MB | 0B |
| `localEvaluation.getMapOfValue` | 73.44MB | 69.30MB | 114.11MB | 0B |
| `utils.ParseFeatureFlag` | 73.44MB | 69.30MB | 114.11MB | 0B |

**Total FF alloc (current snapshot):** 394.37MB  |  **24h avg:** 604.63MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 67.53MB | 30/1030 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 60.16MB | 18/1030 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 681/1030 | `████████░░░░░░░ 54%` |
| 4 | `database/sql.convertAssignRows` | 33.87MB | 38/1030 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 21.16MB | 681/1030 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1030 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 13.33MB | 486/1030 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.72MB | 19/1030 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1030 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1030 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1030 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1030 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1030 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1030 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1030 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.93GB | 654/1030 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1030 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.71GB | 585/1030 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1030 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1030 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.2x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
