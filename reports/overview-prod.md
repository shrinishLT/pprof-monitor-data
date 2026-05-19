# Overview: prod
*Last updated: 2026-05-19 21:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T21:02 (203 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,273 | avg: 15,399 | max: 84,644 | trend: decreasing (-2.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁
```

**Heap InUse** (current: 280.2MB | avg: 231.0MB | max: 1896.6MB | trend: stable (+0.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,273 | 15,123 | +150 | 15,399 | 84,644 | decreasing (-2.42/hr) |
| Heap InUse | 280.2MB | 195.5MB | +84.7MB | 231.0MB | 1896.6MB | stable (+0.18MB/hr) |
| Heap Sys | 4941.7MB | 4941.2MB | +0.5MB | 4507.5MB | 6579.6MB | |
| Heap Objects | 1,317,574 | 648,395 | +669179 | 986,290 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 43 | 15,345 | 233.5MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 7.04MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 7 | `bufio.NewWriterSize` | 4.02MB |
| 8 | `bufio.NewReaderSize` | 2.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 209.52GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 125.91GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 125.67GB |
| 4 | `experiment/local.topologicalSort` | 83.46GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 65.2GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 61.69GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 39.75GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.35GB |
| 9 | `fmt.Sprintf` | 21.38GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 20.63GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/203 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/203 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 201/203 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/203 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.75MB | 201/203 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/203 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/203 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 12.03MB | 126/203 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.43MB | 20/203 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 199/203 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.6GB | 192/203 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.14GB | 198/203 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.04GB | 198/203 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.27GB | 193/203 | `████████░░░░░░░ 54%` |
| 5 | `experiment/local.topologicalSort` | 50.7GB | 180/203 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.33GB | 148/203 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.12GB | 126/203 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.03GB | 184/203 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/203 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 23.42GB | 63/203 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
