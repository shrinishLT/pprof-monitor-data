# Overview: prod
*Last updated: 2026-05-20 00:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T00:30 (210 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,819 | avg: 15,386 | max: 84,644 | trend: decreasing (-2.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 213.4MB | avg: 230.0MB | max: 1896.6MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁▁▁▃▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,819 | 14,487 | +332 | 15,386 | 84,644 | decreasing (-2.91/hr) |
| Heap InUse | 213.4MB | 151.8MB | +61.6MB | 230.0MB | 1896.6MB | stable (+0.11MB/hr) |
| Heap Sys | 4945.2MB | 4944.5MB | +0.7MB | 4522.1MB | 6579.6MB | |
| Heap Objects | 1,050,216 | 468,744 | +581472 | 981,312 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 2 | 14,653 | 182.6MB | 213.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 39.69MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 27.0MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 20.33MB |
| 5 | `runtime.mallocgc` | 20.22MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 8 | `bytes.growSlice` | 8.54MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 10 | `bufio.NewWriterSize` | 4.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 255.14GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 153.58GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 153.24GB |
| 4 | `experiment/local.topologicalSort` | 101.72GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 79.38GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 72.77GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 48.52GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 33.47GB |
| 9 | `fmt.Sprintf` | 25.95GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 22.49GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/210 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/210 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 208/210 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/210 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.56MB | 208/210 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/210 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/210 | `███░░░░░░░░░░░░ 21%` |
| 8 | `bytes.growSlice` | 11.91MB | 131/210 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.25MB | 22/210 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 206/210 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.56GB | 199/210 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.49GB | 205/210 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.41GB | 205/210 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.23GB | 200/210 | `███████░░░░░░░░ 53%` |
| 5 | `experiment/local.topologicalSort` | 52.29GB | 187/210 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.47GB | 155/210 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.76GB | 133/210 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.03GB | 191/210 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/210 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.47GB | 70/210 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
