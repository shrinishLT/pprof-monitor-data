# Overview: prod
*Last updated: 2026-05-18 17:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T17:33 (143 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,433 | avg: 15,286 | max: 84,644 | trend: decreasing (-18.69/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁
```

**Heap InUse** (current: 208.7MB | avg: 217.9MB | max: 1896.6MB | trend: decreasing (-0.80MB/hr))
```
▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,433 | 15,160 | -727 | 15,286 | 84,644 | decreasing (-18.69/hr) |
| Heap InUse | 208.7MB | 301.6MB | -92.9MB | 217.9MB | 1896.6MB | decreasing (-0.80MB/hr) |
| Heap Sys | 6176.3MB | 6172.2MB | +4.1MB | 4384.8MB | 6179.8MB | |
| Heap Objects | 544,903 | 1,166,052 | -621149 | 948,376 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 36 | 15,254 | 231.2MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `experiment/local.topologicalSort` | 4.54MB |
| 7 | `bytes.growSlice` | 3.52MB |
| 8 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 9 | `bufio.NewWriterSize` | 3.03MB |
| 10 | `experiment/local.(*Client).EvaluateV2` | 2.57MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 385.06GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 233.2GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 232.55GB |
| 4 | `experiment/local.topologicalSort` | 153.9GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.34GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 120.61GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 73.63GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.89GB |
| 9 | `fmt.Sprintf` | 36.85GB |
| 10 | `segmentio/kafka-go.makePartitions` | 34.93GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/143 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 141/143 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 23.84MB | 141/143 | `█████████░░░░░░ 64%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/143 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/143 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/143 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/143 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.36MB | 75/143 | `█████░░░░░░░░░░ 33%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/143 | `████░░░░░░░░░░░ 33%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.48MB | 40/143 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 70.95GB | 132/143 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 63.01GB | 136/143 | `█████████████░░ 88%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 41.73GB | 138/143 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 41.69GB | 138/143 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.49GB | 88/143 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 30.19GB | 120/143 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 27.06GB | 134/143 | `█████░░░░░░░░░░ 38%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/143 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.growslice` | 22.61GB | 47/143 | `████░░░░░░░░░░░ 31%` |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 21.23GB | 67/143 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
