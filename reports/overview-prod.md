# Overview: prod
*Last updated: 2026-05-27 02:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T02:32 (570 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,823 | avg: 15,610 | max: 84,644 | trend: decreasing (-0.52/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 198.5MB | avg: 229.5MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▄▄▅▃▄▃▂▅▃▂▄▃▃▅▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▃▁▁▄▁▃▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,823 | 16,281 | -1458 | 15,610 | 84,644 | decreasing (-0.52/hr) |
| Heap InUse | 198.5MB | 282.3MB | -83.8MB | 229.5MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 4466.2MB | 4465.3MB | +0.9MB | 4164.7MB | 6883.9MB | |
| Heap Objects | 981,633 | 1,246,030 | -264397 | 982,281 | 8,100,802 | |

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
| 2026-05-27 | 6 | 15,272 | 215.7MB | 282.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 16.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 4.41MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `aws/endpoints.init` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.04MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.61GB |
| 2 | `fmt.Sprintf` | 21.82GB |
| 3 | `segmentio/kafka-go.makePartitions` | 20.76GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 19.47GB |
| 5 | `jackskj/carta.getUniqueId` | 14.81GB |
| 6 | `reflect.growslice` | 14.6GB |
| 7 | `reflect.unsafe_New` | 12.96GB |
| 8 | `reflect.unsafe_NewArray` | 10.69GB |
| 9 | `strconv.appendQuotedWith` | 10.67GB |
| 10 | `fmt.Sprint` | 10.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/570 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.02MB | 22/570 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 568/570 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 26.52MB | 28/570 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 22.69MB | 568/570 | `███████░░░░░░░░ 48%` |
| 6 | `bytes.growSlice` | 13.27MB | 384/570 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/570 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/570 | `███░░░░░░░░░░░░ 22%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/570 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/570 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/570 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/570 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/570 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/570 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.78GB | 545/570 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/570 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/570 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.32GB | 501/570 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.45GB | 249/570 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.75GB | 362/570 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
