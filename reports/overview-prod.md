# Overview: prod
*Last updated: 2026-05-27 16:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T16:01 (597 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,956 | avg: 15,629 | max: 84,644 | trend: stable (-0.10/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▅▁▂▁▁▁▃▁▁▁▁▁▁
```

**Heap InUse** (current: 229.1MB | avg: 230.5MB | max: 1896.6MB | trend: stable (-0.04MB/hr))
```
▂▅▂▂▄▃▃▄▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▂▁▁▄▁▂▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂▁▃▂▁▂▁▇▄▁▁▁▁▂▁▅▃▄▁▁▁▄▃▂▂▃▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,956 | 14,572 | +1384 | 15,629 | 84,644 | stable (-0.10/hr) |
| Heap InUse | 229.1MB | 156.7MB | +72.4MB | 230.5MB | 1896.6MB | stable (-0.04MB/hr) |
| Heap Sys | 900.9MB | 909.0MB | -8.1MB | 4080.1MB | 6883.9MB | |
| Heap Objects | 877,501 | 766,358 | +111143 | 987,268 | 8,100,802 | |

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
| 2026-05-27 | 33 | 15,880 | 245.1MB | 615.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.65MB |
| 3 | `runtime.mallocgc` | 12.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.04MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `bufio.NewReaderSize` | 4.02MB |
| 9 | `bufio.NewWriterSize` | 3.04MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 4.66GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 1.79GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.21GB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 726.65MB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 716.52MB |
| 6 | `database/sql.convertAssignRows` | 706.04MB |
| 7 | `reflect.unsafe_NewArray` | 638.3MB |
| 8 | `fmt.Sprintf` | 623.69MB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 589.76MB |
| 10 | `reflect.MakeSlice` | 346.51MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.39MB | 25/597 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.31MB | 15/597 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 595/597 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.56MB | 31/597 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.36MB | 595/597 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.3MB | 409/597 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/597 | `███░░░░░░░░░░░░ 24%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/597 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/597 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 588/597 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/597 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/597 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/597 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/597 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.44GB | 572/597 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/597 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/597 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.72GB | 525/597 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 16.81GB | 262/597 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.27GB | 378/597 | `█░░░░░░░░░░░░░░ 11%` |

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
