# Overview: prod
*Last updated: 2026-05-27 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T13:31 (592 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,912 | avg: 15,634 | max: 84,644 | trend: stable (+0.02/hr))
```
▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▅▁▂▁▁▁▃▁
```

**Heap InUse** (current: 271.4MB | avg: 230.6MB | max: 1896.6MB | trend: stable (-0.04MB/hr))
```
▄▅▃▄▃▂▅▂▂▄▃▃▄▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▂▁▁▄▁▂▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂▁▃▂▁▂▁▇▄▁▁▁▁▂▁▅▃▄▁▁▁▄▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,912 | 21,879 | -5967 | 15,634 | 84,644 | stable (+0.02/hr) |
| Heap InUse | 271.4MB | 415.8MB | -144.4MB | 230.6MB | 1896.6MB | stable (-0.04MB/hr) |
| Heap Sys | 4062.7MB | 838.1MB | +3224.6MB | 4096.9MB | 6883.9MB | |
| Heap Objects | 1,387,644 | 1,603,342 | -215698 | 985,956 | 8,100,802 | |

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
| 2026-05-27 | 28 | 16,043 | 249.4MB | 615.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `bufio.NewReaderSize` | 3.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 10.47GB |
| 2 | `reflect.growslice` | 5.5GB |
| 3 | `jackskj/carta.getUniqueId` | 5.15GB |
| 4 | `reflect.unsafe_New` | 4.42GB |
| 5 | `fmt.Sprintf` | 4.4GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 4.06GB |
| 7 | `carta/value.NewCell` | 3.13GB |
| 8 | `fmt.(*buffer).writeString` | 3.12GB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.93GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.25GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.74MB | 24/592 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 44.33MB | 14/592 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 590/592 | `███████████░░░░ 73%` |
| 4 | `database/sql.convertAssignRows` | 27.57MB | 30/592 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.45MB | 590/592 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.32MB | 405/592 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/592 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/592 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/592 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/592 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/592 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/592 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/592 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/592 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.82GB | 567/592 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/592 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/592 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.91GB | 520/592 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.03GB | 258/592 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.43GB | 373/592 | `█░░░░░░░░░░░░░░ 11%` |

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
