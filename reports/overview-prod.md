# Overview: prod
*Last updated: 2026-05-18 18:56 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:56 (149 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,972 | avg: 15,306 | max: 84,644 | trend: decreasing (-14.96/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁
```

**Heap InUse** (current: 370.1MB | avg: 222.1MB | max: 1896.6MB | trend: stable (-0.39MB/hr))
```
▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▁▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆▄▄▃▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,972 | 15,474 | +498 | 15,306 | 84,644 | decreasing (-14.96/hr) |
| Heap InUse | 370.1MB | 248.1MB | +122.0MB | 222.1MB | 1896.6MB | stable (-0.39MB/hr) |
| Heap Sys | 6170.2MB | 6170.7MB | -0.5MB | 4456.8MB | 6179.8MB | |
| Heap Objects | 1,670,144 | 455,163 | +1214981 | 968,503 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 42 | 15,332 | 244.2MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.67MB |
| 5 | `bufio.NewReaderSize` | 6.02MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 3.5MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 420.58GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 254.67GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 253.93GB |
| 4 | `experiment/local.topologicalSort` | 167.97GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 131.84GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 80.4GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.91GB |
| 9 | `fmt.Sprintf` | 40.7GB |
| 10 | `segmentio/kafka-go.makePartitions` | 36.79GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/149 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 147/149 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 25.11MB | 147/149 | `██████████░░░░░ 68%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/149 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/149 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/149 | `███████░░░░░░░░ 46%` |
| 7 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/149 | `████░░░░░░░░░░░ 33%` |
| 8 | `bytes.growSlice` | 12.17MB | 81/149 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/149 | `████░░░░░░░░░░░ 28%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/149 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 85.86GB | 138/149 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 66.07GB | 142/149 | `███████████░░░░ 76%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 50.43GB | 144/149 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 50.37GB | 144/149 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.82GB | 94/149 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 36.63GB | 126/149 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 28.56GB | 140/149 | `████░░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 25.99GB | 73/149 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/149 | `████░░░░░░░░░░░ 28%` |
| 10 | `reflect.growslice` | 22.61GB | 47/149 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
