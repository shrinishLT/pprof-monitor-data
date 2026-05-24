# Overview: prod
*Last updated: 2026-05-24 12:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T12:00 (447 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,168 | avg: 15,675 | max: 84,644 | trend: INCREASING (+0.60/hr))
```
▁▁▁▁▁▁▁▂▁▂▁▂▂▁▁▂▁▁▁▂▃▁▅▄▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁
```

**Heap InUse** (current: 258.5MB | avg: 231.9MB | max: 1896.6MB | trend: stable (-0.09MB/hr))
```
▂▁▂▁▂▂▂▃▁▃▁▂▃▁▂▁▁▁▁▃▃▁▃▄▂▂▂▂▂▁▁▁▁▁▁▄▁▁▁▁▁▁▂▃▂▂▃▁▁▂▁▁▂▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▂▁▁▂▁▁▁▂█▃▄▄▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,168 | 15,853 | -685 | 15,675 | 84,644 | INCREASING (+0.60/hr) |
| Heap InUse | 258.5MB | 354.4MB | -95.9MB | 231.9MB | 1896.6MB | stable (-0.09MB/hr) |
| Heap Sys | 5932.3MB | 5930.0MB | +2.3MB | 4217.9MB | 6883.9MB | |
| Heap Objects | 499,175 | 1,511,374 | -1012199 | 987,303 | 8,100,802 | |

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
| 2026-05-24 | 25 | 15,038 | 203.5MB | 622.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 48.11MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.6MB |
| 5 | `compress/flate.NewWriter` | 6.17MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `bufio.NewReaderSize` | 3.51MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 2.14MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 138.38GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.76GB |
| 3 | `segmentio/kafka-go.makePartitions` | 29.29GB |
| 4 | `reflect.growslice` | 26.78GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 23.16GB |
| 6 | `jackskj/carta.getUniqueId` | 22.66GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 20.67GB |
| 8 | `reflect.unsafe_New` | 20.58GB |
| 9 | `database/sql.convertAssignRows` | 15.76GB |
| 10 | `fmt.(*buffer).writeString` | 15.18GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.33MB | 10/447 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.59MB | 17/447 | `████████████░░░ 80%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 445/447 | `██████████░░░░░ 67%` |
| 4 | `database/sql.convertAssignRows` | 28.62MB | 21/447 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 22.58MB | 445/447 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.67MB | 303/447 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/447 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/447 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/447 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/447 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/447 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/447 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/447 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.67GB | 422/447 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/447 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/447 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/447 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.56GB | 379/447 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/447 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `fmt.(*buffer).writeString` | 18.11GB | 24/447 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
