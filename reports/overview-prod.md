# Overview: prod
*Last updated: 2026-05-22 22:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T22:02 (371 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,793 | avg: 15,809 | max: 84,644 | trend: INCREASING (+6.47/hr))
```
▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 302.8MB | avg: 240.9MB | max: 1896.6MB | trend: stable (+0.20MB/hr))
```
▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,793 | 14,597 | +2196 | 15,809 | 84,644 | INCREASING (+6.47/hr) |
| Heap InUse | 302.8MB | 142.5MB | +160.3MB | 240.9MB | 1896.6MB | stable (+0.20MB/hr) |
| Heap Sys | 2901.2MB | 2902.7MB | -1.5MB | 4279.6MB | 6579.6MB | |
| Heap Objects | 1,615,782 | 587,331 | +1028451 | 1,006,132 | 8,100,802 | |

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
| 2026-05-22 | 47 | 16,012 | 232.7MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 20.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `runtime.mallocgc` | 9.08MB |
| 5 | `bufio.NewReaderSize` | 8.56MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 7 | `bufio.NewWriterSize` | 7.03MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 30.71GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 18.57GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 18.56GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 12.93GB |
| 5 | `experiment/local.topologicalSort` | 12.27GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.55GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 5.97GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 4.95GB |
| 9 | `segmentio/kafka-go.makePartitions` | 4.4GB |
| 10 | `fmt.Sprintf` | 3.62GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/371 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/371 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 369/371 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/371 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.88MB | 369/371 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.01MB | 266/371 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/371 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/371 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/371 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.25MB | 58/371 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 130.91GB | 360/371 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.77GB | 366/371 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.75GB | 366/371 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.62GB | 348/371 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.36GB | 347/371 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.94GB | 316/371 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.49GB | 292/371 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.39GB | 306/371 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/371 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.14GB | 188/371 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
