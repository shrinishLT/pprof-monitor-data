# Overview: prod
*Last updated: 2026-05-20 12:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T12:30 (234 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,720 | avg: 15,506 | max: 84,644 | trend: INCREASING (+3.72/hr))
```
▁▂▁▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁
```

**Heap InUse** (current: 193.3MB | avg: 231.5MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▂▃▂▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,720 | 16,377 | +343 | 15,506 | 84,644 | INCREASING (+3.72/hr) |
| Heap InUse | 193.3MB | 226.9MB | -33.6MB | 231.5MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 796.7MB | 805.2MB | -8.5MB | 4429.7MB | 6579.6MB | |
| Heap Objects | 385,489 | 1,076,095 | -690606 | 981,940 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 26 | 16,410 | 240.0MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 16.58MB |
| 3 | `runtime.mallocgc` | 13.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 9.05MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 8 | `bufio.NewReaderSize` | 6.02MB |
| 9 | `net/http.cloneTLSConfig` | 3.0MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 45.99GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 27.67GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 27.49GB |
| 4 | `experiment/local.topologicalSort` | 18.32GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.41GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 8.7GB |
| 7 | `fmt.Sprintf` | 4.2GB |
| 8 | `reflect.growslice` | 3.6GB |
| 9 | `jackskj/carta.getUniqueId` | 3.26GB |
| 10 | `internal/evaluation.coerceString` | 2.97GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/234 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/234 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 232/234 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/234 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.68MB | 232/234 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/234 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.89MB | 147/234 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/234 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/234 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 228/234 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 123.41GB | 223/234 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.95GB | 229/234 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.88GB | 229/234 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 63.64GB | 222/234 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.5GB | 211/234 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.74GB | 179/234 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.26GB | 156/234 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.18GB | 210/234 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/234 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.21GB | 81/234 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
