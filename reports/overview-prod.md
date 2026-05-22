# Overview: prod
*Last updated: 2026-05-22 22:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T22:30 (372 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,044 | avg: 15,817 | max: 84,644 | trend: INCREASING (+6.70/hr))
```
▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 311.3MB | avg: 241.1MB | max: 1896.6MB | trend: stable (+0.21MB/hr))
```
▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,044 | 16,793 | +2251 | 15,817 | 84,644 | INCREASING (+6.70/hr) |
| Heap InUse | 311.3MB | 302.8MB | +8.5MB | 241.1MB | 1896.6MB | stable (+0.21MB/hr) |
| Heap Sys | 2870.5MB | 2901.2MB | -30.7MB | 4275.9MB | 6579.6MB | |
| Heap Objects | 673,505 | 1,615,782 | -942277 | 1,005,238 | 8,100,802 | |

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
| 2026-05-22 | 48 | 16,075 | 234.3MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 32.16MB |
| 3 | `runtime.mallocgc` | 14.51MB |
| 4 | `bufio.NewReaderSize` | 13.06MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 7 | `bufio.NewWriterSize` | 8.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `net/http.(*Transport).dialConn` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 43.0GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 25.96GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 25.86GB |
| 4 | `experiment/local.topologicalSort` | 17.09GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.46GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 12.96GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 8.32GB |
| 8 | `segmentio/kafka-go.makePartitions` | 5.07GB |
| 9 | `fmt.Sprintf` | 5.06GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 4.97GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/372 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/372 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 370/372 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/372 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.85MB | 370/372 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.08MB | 267/372 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/372 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/372 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/372 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.25MB | 58/372 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 130.67GB | 361/372 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.63GB | 367/372 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.61GB | 367/372 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.51GB | 349/372 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.25GB | 348/372 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.84GB | 317/372 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.42GB | 293/372 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.33GB | 307/372 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/372 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.06GB | 189/372 | `██░░░░░░░░░░░░░ 14%` |

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
