# Overview: prod
*Last updated: 2026-05-26 11:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T11:03 (541 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,767 | avg: 15,613 | max: 84,644 | trend: decreasing (-0.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁
```

**Heap InUse** (current: 305.0MB | avg: 230.4MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▃▂▄▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▁▅▂▄▂▂▃▃▅▃▄▃▂▄▂▂▃▃▃▄▂▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁▇▁▃▁▁▁▁▁▁▁▄▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,767 | 23,713 | -8946 | 15,613 | 84,644 | decreasing (-0.54/hr) |
| Heap InUse | 305.0MB | 510.3MB | -205.3MB | 230.4MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 4478.0MB | 4430.9MB | +47.1MB | 4192.2MB | 6883.9MB | |
| Heap Objects | 1,572,815 | 1,418,583 | +154232 | 986,323 | 8,100,802 | |

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
| 2026-05-26 | 23 | 16,045 | 218.6MB | 639.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.61MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.19MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `bufio.NewWriterSize` | 4.04MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `aws/endpoints.init` | 3.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.84GB |
| 2 | `reflect.growslice` | 22.25GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.21GB |
| 4 | `jackskj/carta.getUniqueId` | 19.11GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 18.7GB |
| 6 | `reflect.unsafe_New` | 16.97GB |
| 7 | `fmt.(*buffer).writeString` | 12.77GB |
| 8 | `carta/value.NewCell` | 12.31GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.27GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.77GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 48.86MB | 21/541 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/541 | `██████████████░ 96%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 539/541 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 28.33MB | 26/541 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 23.08MB | 539/541 | `███████░░░░░░░░ 47%` |
| 6 | `bytes.growSlice` | 13.47MB | 359/541 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/541 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/541 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/541 | `███░░░░░░░░░░░░ 21%` |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 10.5MB | 8/541 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/541 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/541 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/541 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.24GB | 516/541 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/541 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/541 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/541 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.13GB | 472/541 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 17.97GB | 223/541 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.08GB | 333/541 | `█░░░░░░░░░░░░░░ 12%` |

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
