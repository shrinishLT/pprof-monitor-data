# Overview: prod
*Last updated: 2026-05-26 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T08:01 (535 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,625 | avg: 15,597 | max: 84,644 | trend: decreasing (-0.91/hr))
```
▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁
```

**Heap InUse** (current: 175.9MB | avg: 229.9MB | max: 1896.6MB | trend: stable (-0.08MB/hr))
```
▁▁▂▇▃▃▃▂▄▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▁▅▂▄▂▂▃▃▅▃▄▃▂▄▂▂▃▃▃▄▂▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁▇▁▃▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,625 | 14,319 | +306 | 15,597 | 84,644 | decreasing (-0.91/hr) |
| Heap InUse | 175.9MB | 140.0MB | +35.9MB | 229.9MB | 1896.6MB | stable (-0.08MB/hr) |
| Heap Sys | 3632.1MB | 3632.8MB | -0.7MB | 4190.5MB | 6883.9MB | |
| Heap Objects | 1,050,580 | 591,244 | +459336 | 985,387 | 8,100,802 | |

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
| 2026-05-26 | 17 | 15,718 | 200.6MB | 639.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewReaderSize` | 3.53MB |
| 7 | `bytes.growSlice` | 3.52MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `aws/endpoints.init` | 3.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.6GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.3GB |
| 3 | `reflect.growslice` | 10.21GB |
| 4 | `jackskj/carta.getUniqueId` | 7.72GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.99GB |
| 6 | `reflect.unsafe_New` | 6.98GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.43GB |
| 8 | `fmt.(*buffer).writeString` | 5.16GB |
| 9 | `carta/value.NewCell` | 5.15GB |
| 10 | `database/sql.convertAssignRows` | 4.86GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 48.86MB | 21/535 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/535 | `██████████████░ 96%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 533/535 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 28.33MB | 26/535 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 23.07MB | 533/535 | `███████░░░░░░░░ 47%` |
| 6 | `bytes.growSlice` | 13.36MB | 354/535 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/535 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/535 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/535 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/535 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/535 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/535 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/535 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.28GB | 510/535 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/535 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/535 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/535 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.2GB | 466/535 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 17.97GB | 223/535 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.18GB | 329/535 | `█░░░░░░░░░░░░░░ 12%` |

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
