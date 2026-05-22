# Overview: prod
*Last updated: 2026-05-22 16:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T16:00 (359 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,585 | avg: 15,814 | max: 84,644 | trend: INCREASING (+7.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 324.8MB | avg: 242.4MB | max: 1896.6MB | trend: stable (+0.27MB/hr))
```
▁▁▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,585 | 14,502 | +3083 | 15,814 | 84,644 | INCREASING (+7.33/hr) |
| Heap InUse | 324.8MB | 194.2MB | +130.6MB | 242.4MB | 1896.6MB | stable (+0.27MB/hr) |
| Heap Sys | 5054.0MB | 5062.8MB | -8.8MB | 4299.2MB | 6579.6MB | |
| Heap Objects | 1,702,599 | 1,071,139 | +631460 | 1,012,650 | 8,100,802 | |

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
| 2026-05-22 | 35 | 16,136 | 244.8MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 26.13MB |
| 3 | `bufio.NewWriterSize` | 11.54MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.54MB |
| 5 | `runtime.mallocgc` | 9.51MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewReaderSize` | 7.53MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 102.27GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 61.42GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 61.23GB |
| 4 | `experiment/local.topologicalSort` | 40.84GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.98GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 21.76GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 19.56GB |
| 8 | `fmt.Sprintf` | 9.65GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 8.26GB |
| 10 | `internal/evaluation.coerceString` | 6.67GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/359 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/359 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 357/359 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/359 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.38MB | 357/359 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.14MB | 256/359 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/359 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/359 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/359 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.51MB | 56/359 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 133.22GB | 348/359 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.1GB | 354/359 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.08GB | 354/359 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.62GB | 336/359 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 53.59GB | 335/359 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.97GB | 304/359 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.23GB | 280/359 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.15GB | 294/359 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/359 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.6GB | 180/359 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
