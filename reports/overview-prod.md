# Overview: prod
*Last updated: 2026-05-20 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T20:02 (249 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,792 | avg: 15,510 | max: 84,644 | trend: INCREASING (+3.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁▁▁▁▁
```

**Heap InUse** (current: 252.1MB | avg: 230.8MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁▁▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,792 | 15,678 | +114 | 15,510 | 84,644 | INCREASING (+3.31/hr) |
| Heap InUse | 252.1MB | 223.6MB | +28.5MB | 230.8MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4980.3MB | 4976.3MB | +4.0MB | 4339.6MB | 6579.6MB | |
| Heap Objects | 1,249,005 | 1,052,432 | +196573 | 983,448 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 41 | 16,106 | 232.6MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `bytes.growSlice` | 11.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 6 | `bufio.NewWriterSize` | 4.53MB |
| 7 | `bufio.NewReaderSize` | 4.53MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 118.44GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 71.6GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 71.15GB |
| 4 | `experiment/local.topologicalSort` | 47.28GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 37.21GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 22.5GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 19.75GB |
| 8 | `fmt.Sprintf` | 13.25GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.38GB |
| 10 | `segmentio/kafka-go.makePartitions` | 9.4GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/249 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/249 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 247/249 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/249 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.03MB | 247/249 | `█████░░░░░░░░░░ 38%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/249 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 12.63MB | 162/249 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/249 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.03MB | 31/249 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/249 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.45GB | 238/249 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.71GB | 244/249 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.65GB | 244/249 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.57GB | 236/249 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.68GB | 226/249 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.6GB | 194/249 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.53GB | 171/249 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.98GB | 221/249 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/249 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.78GB | 96/249 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
