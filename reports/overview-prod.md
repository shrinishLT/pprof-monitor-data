# Overview: prod
*Last updated: 2026-05-25 02:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T02:00 (475 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,309 | avg: 15,596 | max: 84,644 | trend: decreasing (-1.38/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 208.4MB | avg: 228.4MB | max: 1896.6MB | trend: stable (-0.15MB/hr))
```
▂▁▁▁▁▁▁▄▁▁▁▁▁▁▂▃▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,309 | 14,075 | +1234 | 15,596 | 84,644 | decreasing (-1.38/hr) |
| Heap InUse | 208.4MB | 136.4MB | +72.0MB | 228.4MB | 1896.6MB | stable (-0.15MB/hr) |
| Heap Sys | 4158.5MB | 4159.1MB | -0.6MB | 4176.2MB | 6883.9MB | |
| Heap Objects | 987,069 | 777,106 | +209963 | 983,181 | 8,100,802 | |

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
| 2026-05-25 | 5 | 14,410 | 170.6MB | 208.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.01MB |
| 4 | `bytes.growSlice` | 8.55MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewWriterSize` | 5.03MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.27GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 25.73GB |
| 3 | `segmentio/kafka-go.makePartitions` | 15.44GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.87GB |
| 5 | `reflect.unsafe_NewArray` | 7.97GB |
| 6 | `database/sql.convertAssignRows` | 7.71GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.5GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.35GB |
| 9 | `reflect.MakeSlice` | 4.51GB |
| 10 | `reflect.growslice` | 3.83GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.69MB | 11/475 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.2MB | 18/475 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 473/475 | `██████████░░░░░ 69%` |
| 4 | `database/sql.convertAssignRows` | 30.41MB | 22/475 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 21.86MB | 473/475 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.49MB | 310/475 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/475 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/475 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/475 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/475 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/475 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/475 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/475 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.73GB | 450/475 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/475 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/475 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/475 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.86GB | 407/475 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/475 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.88GB | 281/475 | `█░░░░░░░░░░░░░░ 12%` |

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
