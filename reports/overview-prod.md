# Overview: prod
*Last updated: 2026-05-26 06:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T06:01 (531 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,922 | avg: 15,607 | max: 84,644 | trend: decreasing (-0.72/hr))
```
▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁
```

**Heap InUse** (current: 353.6MB | avg: 230.6MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▁▅▂▄▂▂▃▃▅▃▄▃▂▄▂▂▃▃▃▄▂▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁▇▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,922 | 14,967 | -45 | 15,607 | 84,644 | decreasing (-0.72/hr) |
| Heap InUse | 353.6MB | 176.3MB | +177.3MB | 230.6MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 2435.7MB | 744.3MB | +1691.4MB | 4197.0MB | 6883.9MB | |
| Heap Objects | 1,712,265 | 672,805 | +1039460 | 987,715 | 8,100,802 | |

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
| 2026-05-26 | 13 | 16,132 | 217.2MB | 639.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 77.11MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 21.5MB |
| 4 | `runtime.mallocgc` | 10.51MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bytes.growSlice` | 7.04MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 6.59MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 4.0MB |
| 10 | `aws/endpoints.init` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.35GB |
| 2 | `reflect.growslice` | 9.85GB |
| 3 | `jackskj/carta.getUniqueId` | 7.34GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.97GB |
| 5 | `reflect.unsafe_New` | 6.66GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 5.21GB |
| 7 | `fmt.(*buffer).writeString` | 4.98GB |
| 8 | `carta/value.NewCell` | 4.94GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.0GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 48.86MB | 21/531 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/531 | `██████████████░ 96%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 529/531 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 28.33MB | 26/531 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 23.17MB | 529/531 | `███████░░░░░░░░ 47%` |
| 6 | `bytes.growSlice` | 13.42MB | 352/531 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/531 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/531 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/531 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/531 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/531 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/531 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/531 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.36GB | 506/531 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/531 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/531 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/531 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.26GB | 462/531 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 17.97GB | 223/531 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.18GB | 329/531 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
