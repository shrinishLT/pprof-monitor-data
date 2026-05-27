# Overview: prod
*Last updated: 2026-05-27 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T07:31 (580 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,010 | avg: 15,609 | max: 84,644 | trend: decreasing (-0.53/hr))
```
▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 158.4MB | avg: 230.1MB | max: 1896.6MB | trend: stable (-0.06MB/hr))
```
▁▁▁▁▂▁▅▂▄▂▂▄▄▅▃▄▃▂▅▂▂▄▃▃▄▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▂▁▁▄▁▂▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂▁▃▂▁▂▁▇▄▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,010 | 14,588 | +422 | 15,609 | 84,644 | decreasing (-0.53/hr) |
| Heap InUse | 158.4MB | 164.2MB | -5.8MB | 230.1MB | 1896.6MB | stable (-0.06MB/hr) |
| Heap Sys | 3053.6MB | 3053.2MB | +0.4MB | 4129.6MB | 6883.9MB | |
| Heap Objects | 639,106 | 732,546 | -93440 | 984,709 | 8,100,802 | |

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
| 2026-05-27 | 16 | 15,421 | 245.0MB | 615.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 9 | `bufio.NewWriterSize` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.89GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.89GB |
| 3 | `reflect.growslice` | 9.98GB |
| 4 | `jackskj/carta.getUniqueId` | 7.67GB |
| 5 | `reflect.unsafe_New` | 6.94GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.93GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.44GB |
| 8 | `carta/value.NewCell` | 5.02GB |
| 9 | `fmt.(*buffer).writeString` | 5.0GB |
| 10 | `database/sql.convertAssignRows` | 4.89GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.74MB | 24/580 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 44.33MB | 14/580 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 578/580 | `███████████░░░░ 73%` |
| 4 | `database/sql.convertAssignRows` | 27.57MB | 30/580 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.5MB | 578/580 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.17MB | 394/580 | `███░░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/580 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/580 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/580 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/580 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/580 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/580 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/580 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/580 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.24GB | 555/580 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/580 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/580 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.08GB | 510/580 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.33GB | 252/580 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.61GB | 367/580 | `█░░░░░░░░░░░░░░ 11%` |

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
