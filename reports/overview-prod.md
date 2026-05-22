# Overview: prod
*Last updated: 2026-05-23 00:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T00:00 (375 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,073 | avg: 15,847 | max: 84,644 | trend: INCREASING (+7.48/hr))
```
▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂
```

**Heap InUse** (current: 349.0MB | avg: 241.4MB | max: 1896.6MB | trend: stable (+0.21MB/hr))
```
▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,073 | 23,039 | -2966 | 15,847 | 84,644 | INCREASING (+7.48/hr) |
| Heap InUse | 349.0MB | 301.3MB | +47.7MB | 241.4MB | 1896.6MB | stable (+0.21MB/hr) |
| Heap Sys | 2853.1MB | 2876.5MB | -23.4MB | 4264.6MB | 6579.6MB | |
| Heap Objects | 960,730 | 808,634 | +152096 | 1,003,063 | 8,100,802 | |

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
| 2026-05-23 | 1 | 20,073 | 349.0MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 32.16MB |
| 3 | `runtime.mallocgc` | 19.22MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.58MB |
| 5 | `bufio.NewReaderSize` | 16.07MB |
| 6 | `bufio.NewWriterSize` | 13.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 8.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 64.52GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 38.8GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 38.61GB |
| 4 | `experiment/local.topologicalSort` | 25.58GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 22.28GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.17GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 12.43GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.5GB |
| 9 | `fmt.Sprintf` | 7.29GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/375 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/375 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 373/375 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/375 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.78MB | 373/375 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.24MB | 270/375 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/375 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/375 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/375 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.23MB | 59/375 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 130.03GB | 364/375 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.26GB | 370/375 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.24GB | 370/375 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.24GB | 352/375 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.98GB | 351/375 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.57GB | 320/375 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.22GB | 296/375 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.16GB | 310/375 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/375 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.86GB | 192/375 | `██░░░░░░░░░░░░░ 14%` |

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
