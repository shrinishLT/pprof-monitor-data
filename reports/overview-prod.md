# Overview: prod
*Last updated: 2026-05-20 02:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T02:31 (214 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,355 | avg: 15,417 | max: 84,644 | trend: decreasing (-1.05/hr))
```
▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇▁
```

**Heap InUse** (current: 144.0MB | avg: 231.5MB | max: 1896.6MB | trend: stable (+0.19MB/hr))
```
▂▃▁▁▁▁▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,355 | 25,220 | -10865 | 15,417 | 84,644 | decreasing (-1.05/hr) |
| Heap InUse | 144.0MB | 786.9MB | -642.9MB | 231.5MB | 1896.6MB | stable (+0.19MB/hr) |
| Heap Sys | 4898.4MB | 4882.9MB | +15.5MB | 4529.5MB | 6579.6MB | |
| Heap Objects | 277,624 | 3,247,545 | -2969921 | 985,186 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 6 | 16,237 | 268.1MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bufio.NewReaderSize` | 2.52MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 306.67GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 184.54GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 184.32GB |
| 4 | `experiment/local.topologicalSort` | 122.33GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 95.61GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 82.48GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 58.31GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 37.97GB |
| 9 | `fmt.Sprintf` | 31.02GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 23.2GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/214 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/214 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 212/214 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/214 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.46MB | 212/214 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/214 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/214 | `███░░░░░░░░░░░░ 21%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.35MB | 23/214 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `bytes.growSlice` | 12.11MB | 134/214 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 209/214 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.62GB | 203/214 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 75.3GB | 209/214 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 75.23GB | 209/214 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.45GB | 204/214 | `███████░░░░░░░░ 52%` |
| 5 | `experiment/local.topologicalSort` | 53.53GB | 191/214 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.44GB | 159/214 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.36GB | 137/214 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.14GB | 195/214 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/214 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 23.73GB | 74/214 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
