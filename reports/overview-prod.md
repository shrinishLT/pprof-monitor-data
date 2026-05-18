# Overview: prod
*Last updated: 2026-05-18 16:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T16:32 (141 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,843 | avg: 15,293 | max: 84,644 | trend: decreasing (-18.89/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂
```

**Heap InUse** (current: 307.6MB | avg: 217.4MB | max: 1896.6MB | trend: decreasing (-0.88MB/hr))
```
▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,843 | 18,933 | -2090 | 15,293 | 84,644 | decreasing (-18.89/hr) |
| Heap InUse | 307.6MB | 408.3MB | -100.7MB | 217.4MB | 1896.6MB | decreasing (-0.88MB/hr) |
| Heap Sys | 6172.0MB | 6173.7MB | -1.7MB | 4359.4MB | 6179.8MB | |
| Heap Objects | 678,431 | 1,318,924 | -640493 | 949,693 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 34 | 15,281 | 229.8MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `internal/evaluation.mergeMetadata` | 24.01MB |
| 4 | `bytes.growSlice` | 19.61MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.15MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 8.51MB |
| 8 | `experiment/local.topologicalSort` | 6.58MB |
| 9 | `bufio.NewReaderSize` | 6.53MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 371.41GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 225.01GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 224.3GB |
| 4 | `experiment/local.topologicalSort` | 148.41GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 129.68GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 116.49GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 71.08GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 59.27GB |
| 9 | `fmt.Sprintf` | 35.15GB |
| 10 | `segmentio/kafka-go.makePartitions` | 33.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/141 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 139/141 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 23.39MB | 139/141 | `█████████░░░░░░ 63%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/141 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/141 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/141 | `███████░░░░░░░░ 46%` |
| 7 | `internal/evaluation.mergeMetadata` | 13.25MB | 8/141 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/141 | `█████░░░░░░░░░░ 35%` |
| 9 | `bytes.growSlice` | 12.52MB | 73/141 | `█████░░░░░░░░░░ 34%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.62MB | 39/141 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 66.16GB | 130/141 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 61.97GB | 134/141 | `██████████████░ 93%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 38.94GB | 136/141 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 38.91GB | 136/141 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 28.41GB | 86/141 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 28.11GB | 118/141 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.55GB | 132/141 | `██████░░░░░░░░░ 40%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/141 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.growslice` | 22.61GB | 47/141 | `█████░░░░░░░░░░ 34%` |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 19.63GB | 65/141 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
