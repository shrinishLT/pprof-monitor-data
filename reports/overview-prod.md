# Overview: prod
*Last updated: 2026-05-19 22:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T22:00 (205 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,985 | avg: 15,393 | max: 84,644 | trend: decreasing (-2.69/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁
```

**Heap InUse** (current: 191.5MB | avg: 230.6MB | max: 1896.6MB | trend: stable (+0.15MB/hr))
```
▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂▃▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,985 | 14,593 | +392 | 15,393 | 84,644 | decreasing (-2.69/hr) |
| Heap InUse | 191.5MB | 184.3MB | +7.2MB | 230.6MB | 1896.6MB | stable (+0.15MB/hr) |
| Heap Sys | 4943.9MB | 4942.8MB | +1.1MB | 4511.8MB | 6579.6MB | |
| Heap Objects | 649,972 | 762,447 | -112475 | 983,558 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 45 | 15,321 | 231.5MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bufio.NewReaderSize` | 6.55MB |
| 6 | `bytes.growSlice` | 6.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 225.74GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 135.67GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 135.48GB |
| 4 | `experiment/local.topologicalSort` | 90.0GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.24GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 61.73GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 42.83GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.37GB |
| 9 | `fmt.Sprintf` | 23.0GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 20.94GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/205 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/205 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 203/205 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/205 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.69MB | 203/205 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/205 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/205 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.93MB | 128/205 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 21/205 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 201/205 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.64GB | 194/205 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.75GB | 200/205 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.66GB | 200/205 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.22GB | 195/205 | `████████░░░░░░░ 54%` |
| 5 | `experiment/local.topologicalSort` | 51.11GB | 182/205 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.61GB | 150/205 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.27GB | 128/205 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.01GB | 186/205 | `███░░░░░░░░░░░░ 24%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/205 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.4GB | 65/205 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
