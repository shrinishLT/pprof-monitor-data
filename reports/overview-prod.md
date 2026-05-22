# Overview: prod
*Last updated: 2026-05-22 18:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T18:30 (364 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,387 | avg: 15,815 | max: 84,644 | trend: INCREASING (+7.06/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 260.4MB | avg: 242.0MB | max: 1896.6MB | trend: stable (+0.25MB/hr))
```
▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,387 | 16,550 | +837 | 15,815 | 84,644 | INCREASING (+7.06/hr) |
| Heap InUse | 260.4MB | 234.5MB | +25.9MB | 242.0MB | 1896.6MB | stable (+0.25MB/hr) |
| Heap Sys | 5053.6MB | 5052.4MB | +1.2MB | 4309.5MB | 6579.6MB | |
| Heap Objects | 1,085,494 | 1,008,560 | +76934 | 1,010,759 | 8,100,802 | |

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
| 2026-05-22 | 40 | 16,102 | 240.6MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 15.58MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `bufio.NewWriterSize` | 9.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.03MB |
| 7 | `bufio.NewReaderSize` | 5.52MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 137.3GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 82.3GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 82.24GB |
| 4 | `experiment/local.topologicalSort` | 54.61GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.93GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 32.88GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.27GB |
| 8 | `fmt.Sprintf` | 13.65GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 12.47GB |
| 10 | `segmentio/kafka-go.makePartitions` | 9.9GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/364 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/364 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 362/364 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/364 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.19MB | 362/364 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.05MB | 261/364 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/364 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/364 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/364 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.51MB | 56/364 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 133.13GB | 353/364 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.06GB | 359/364 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.04GB | 359/364 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.56GB | 341/364 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 53.25GB | 340/364 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.85GB | 309/364 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.12GB | 285/364 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.91GB | 299/364 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/364 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.41GB | 185/364 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
