# Overview: prod
*Last updated: 2026-06-05 23:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T23:55 (1529 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,428 | avg: 12,323 | max: 84,644 | trend: INCREASING (+0.69/hr))
```
▁▂▅▄▄▃▄▆▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▁▁▁▂▂▂▁▁▁▂▁▃▇▆▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁
```

**Heap InUse** (current: 152.5MB | avg: 186.4MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▁▁▄▅▄▃▅▅▅▄▁▃▁▂▁▁▁▁▂▂▁▂▁▁▁▂▃▂▂▂▂▁▂▁▂▂▃▁▁▁▁▁▁▂▂▂▂▂▂▃▄▂▂▁▂▃▂▁▄▄▂▃▁▂▂▁▃▆█▁▆▁▁▁▂▂▁▁▁▁▂▂▂▂▁▁▂▁▇▅▁▂▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,428 | 14,507 | -79 | 12,323 | 84,644 | INCREASING (+0.69/hr) |
| Heap InUse | 152.5MB | 200.9MB | -48.4MB | 186.4MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1037.2MB | 1036.9MB | +0.3MB | 2544.4MB | 6883.9MB | |
| Heap Objects | 612,374 | 1,167,634 | -555260 | 827,546 | 17,165,538 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bufio.NewWriterSize` | 2.57MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `bytes.growSlice` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 19.2GB |
| 2 | `segmentio/kafka-go.makePartitions` | 17.03GB |
| 3 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 15.05GB |
| 4 | `jackskj/carta.getUniqueId` | 14.85GB |
| 5 | `reflect.growslice` | 14.11GB |
| 6 | `reflect.unsafe_New` | 12.35GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.96GB |
| 8 | `fmt.(*buffer).writeString` | 9.93GB |
| 9 | `strconv.appendQuotedWith` | 9.26GB |
| 10 | `fmt.Sprint` | 9.23GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.14GB | 1.14GB | 1012.74MB | 0B |
| `evaluation.mergeMetadata` | 605.15MB | 604.15MB | 520.02MB | 0B |
| `local.(*Client).EvaluateV2` | 1.75GB | 1.75GB | 1.53GB | 0B |
| `local.topologicalSort` | 256.54MB | 256.04MB | 225.03MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.65GB | 1.65GB | 1.44GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 265.75MB | 265.75MB | 240.98MB | 0B |
| `localEvaluation.getMapOfValue` | 1.65GB | 1.65GB | 1.44GB | 0B |
| `utils.ParseFeatureFlag` | 1.66GB | 1.65GB | 1.44GB | 0B |

**Total FF alloc (current snapshot):** 8.96GB  |  **24h avg:** 7.79GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1529 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1529 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1529 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1180/1529 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1529 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.2MB | 1180/1529 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.7MB | 925/1529 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1529 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1529 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1529 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1529 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1529 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1529 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1529 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1529 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1529 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1529 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1529 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.69GB | 241/1529 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.29GB | 713/1529 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.9x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
