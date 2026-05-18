# Overview: prod
*Last updated: 2026-05-18 17:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T17:02 (142 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,160 | avg: 15,292 | max: 84,644 | trend: decreasing (-18.57/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁
```

**Heap InUse** (current: 301.6MB | avg: 218.0MB | max: 1896.6MB | trend: decreasing (-0.82MB/hr))
```
▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,160 | 16,843 | -1683 | 15,292 | 84,644 | decreasing (-18.57/hr) |
| Heap InUse | 301.6MB | 307.6MB | -6.0MB | 218.0MB | 1896.6MB | decreasing (-0.82MB/hr) |
| Heap Sys | 6172.2MB | 6172.0MB | +0.2MB | 4372.2MB | 6179.8MB | |
| Heap Objects | 1,166,052 | 678,431 | +487621 | 951,217 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 35 | 15,277 | 231.8MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 10.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 5.03MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 379.02GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 229.58GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 228.88GB |
| 4 | `experiment/local.topologicalSort` | 151.45GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 130.43GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 118.76GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 72.5GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 59.61GB |
| 9 | `fmt.Sprintf` | 36.21GB |
| 10 | `segmentio/kafka-go.makePartitions` | 34.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/142 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 140/142 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 23.61MB | 140/142 | `█████████░░░░░░ 64%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/142 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/142 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/142 | `███████░░░░░░░░ 46%` |
| 7 | `internal/evaluation.mergeMetadata` | 13.25MB | 8/142 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/142 | `█████░░░░░░░░░░ 35%` |
| 9 | `bytes.growSlice` | 12.48MB | 74/142 | `█████░░░░░░░░░░ 33%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.48MB | 40/142 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 68.55GB | 131/142 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.48GB | 135/142 | `█████████████░░ 91%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 40.33GB | 137/142 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 40.3GB | 137/142 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.45GB | 87/142 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 29.15GB | 119/142 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.8GB | 133/142 | `█████░░░░░░░░░░ 39%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/142 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.growslice` | 22.61GB | 47/142 | `████░░░░░░░░░░░ 32%` |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 20.43GB | 66/142 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
