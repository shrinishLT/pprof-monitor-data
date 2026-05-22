# Overview: prod
*Last updated: 2026-05-22 23:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T23:32 (374 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 23,039 | avg: 15,835 | max: 84,644 | trend: INCREASING (+7.17/hr))
```
▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂
```

**Heap InUse** (current: 301.3MB | avg: 241.1MB | max: 1896.6MB | trend: stable (+0.20MB/hr))
```
▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 27%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 23,039 | 15,352 | +7687 | 15,835 | 84,644 | INCREASING (+7.17/hr) |
| Heap InUse | 301.3MB | 168.1MB | +133.2MB | 241.1MB | 1896.6MB | stable (+0.20MB/hr) |
| Heap Sys | 2876.5MB | 2876.7MB | -0.2MB | 4268.4MB | 6579.6MB | |
| Heap Objects | 808,634 | 430,642 | +377992 | 1,003,176 | 8,100,802 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 46.22MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewWriterSize` | 25.1MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.11MB |
| 5 | `bufio.NewReaderSize` | 20.09MB |
| 6 | `runtime.mallocgc` | 14.51MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 7.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 6.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 51.42GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 30.92GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 30.85GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 22.24GB |
| 5 | `experiment/local.topologicalSort` | 20.44GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.06GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 9.9GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.48GB |
| 9 | `segmentio/kafka-go.makePartitions` | 6.46GB |
| 10 | `fmt.Sprintf` | 5.95GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/374 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/374 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 372/374 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/374 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.8MB | 372/374 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.18MB | 269/374 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/374 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/374 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/374 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.23MB | 59/374 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 130.22GB | 363/374 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.36GB | 369/374 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.34GB | 369/374 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.32GB | 351/374 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.06GB | 350/374 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.65GB | 319/374 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.28GB | 295/374 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.21GB | 309/374 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/374 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.92GB | 191/374 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
