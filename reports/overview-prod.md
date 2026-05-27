# Overview: prod
*Last updated: 2026-05-27 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T05:31 (576 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,288 | avg: 15,614 | max: 84,644 | trend: stable (-0.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 174.1MB | avg: 229.4MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▁▂▁▂▁▁▁▁▂▁▅▂▄▂▂▄▄▅▃▄▃▂▅▂▂▄▃▃▄▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▂▁▁▄▁▂▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂▁▃▂▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,288 | 15,462 | +826 | 15,614 | 84,644 | stable (-0.43/hr) |
| Heap InUse | 174.1MB | 261.1MB | -87.0MB | 229.4MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 1161.9MB | 1290.9MB | -129.0MB | 4138.6MB | 6883.9MB | |
| Heap Objects | 382,784 | 879,656 | -496872 | 980,614 | 8,100,802 | |

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
| 2026-05-27 | 12 | 15,610 | 215.8MB | 335.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.08MB |
| 3 | `runtime.mallocgc` | 12.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 7 | `bufio.NewReaderSize` | 6.02MB |
| 8 | `bufio.NewWriterSize` | 5.03MB |
| 9 | `reflect.unsafe_NewArray` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 7.79GB |
| 2 | `jackskj/carta.getUniqueId` | 5.9GB |
| 3 | `reflect.unsafe_New` | 5.39GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 4.46GB |
| 5 | `fmt.(*buffer).writeString` | 3.91GB |
| 6 | `carta/value.NewCell` | 3.88GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 2.64GB |
| 8 | `fmt.(*buffer).writeByte` | 1.44GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.3GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/576 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.02MB | 22/576 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 574/576 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 26.52MB | 28/576 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 22.58MB | 574/576 | `███████░░░░░░░░ 47%` |
| 6 | `bytes.growSlice` | 13.25MB | 390/576 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/576 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/576 | `███░░░░░░░░░░░░ 22%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/576 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/576 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/576 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/576 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/576 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/576 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.35GB | 551/576 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/576 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/576 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.15GB | 506/576 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.33GB | 252/576 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.61GB | 367/576 | `█░░░░░░░░░░░░░░ 11%` |

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
