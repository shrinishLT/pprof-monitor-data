# Overview: prod
*Last updated: 2026-05-27 07:04 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T07:04 (579 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,588 | avg: 15,610 | max: 84,644 | trend: decreasing (-0.51/hr))
```
▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 164.2MB | avg: 230.2MB | max: 1896.6MB | trend: stable (-0.05MB/hr))
```
▂▁▁▁▁▂▁▅▂▄▂▂▄▄▅▃▄▃▂▅▂▂▄▃▃▄▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▂▁▁▄▁▂▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂▁▃▂▁▂▁▇▄▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,588 | 15,075 | -487 | 15,610 | 84,644 | decreasing (-0.51/hr) |
| Heap InUse | 164.2MB | 391.4MB | -227.2MB | 230.2MB | 1896.6MB | stable (-0.05MB/hr) |
| Heap Sys | 3053.2MB | 3051.9MB | +1.3MB | 4131.5MB | 6883.9MB | |
| Heap Objects | 732,546 | 2,419,553 | -1687007 | 985,306 | 8,100,802 | |

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
| 2026-05-27 | 15 | 15,448 | 250.8MB | 615.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bytes.growSlice` | 4.02MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `bufio.NewReaderSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.89GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.89GB |
| 3 | `reflect.growslice` | 9.83GB |
| 4 | `jackskj/carta.getUniqueId` | 7.48GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.9GB |
| 6 | `reflect.unsafe_New` | 6.8GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.42GB |
| 8 | `fmt.(*buffer).writeString` | 4.94GB |
| 9 | `carta/value.NewCell` | 4.92GB |
| 10 | `database/sql.convertAssignRows` | 4.88GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.74MB | 24/579 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 44.33MB | 14/579 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 577/579 | `███████████░░░░ 73%` |
| 4 | `database/sql.convertAssignRows` | 27.57MB | 30/579 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.52MB | 577/579 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.19MB | 393/579 | `███░░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/579 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/579 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/579 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/579 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/579 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/579 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/579 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/579 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.25GB | 554/579 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/579 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/579 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.09GB | 509/579 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.33GB | 252/579 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.61GB | 367/579 | `█░░░░░░░░░░░░░░ 11%` |

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
