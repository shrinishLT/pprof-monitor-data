# Overview: prod
*Last updated: 2026-05-18 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T15:03 (138 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,705 | avg: 15,259 | max: 84,644 | trend: decreasing (-23.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁
```

**Heap InUse** (current: 241.0MB | avg: 214.5MB | max: 1896.6MB | trend: decreasing (-1.20MB/hr))
```
▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,705 | 15,442 | -737 | 15,259 | 84,644 | decreasing (-23.18/hr) |
| Heap InUse | 241.0MB | 268.7MB | -27.7MB | 214.5MB | 1896.6MB | decreasing (-1.20MB/hr) |
| Heap Sys | 6176.5MB | 6173.2MB | +3.3MB | 4320.0MB | 6176.5MB | |
| Heap Objects | 629,031 | 937,181 | -308150 | 944,904 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 31 | 15,129 | 218.3MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 6.17MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bytes.growSlice` | 3.07MB |
| 7 | `bufio.NewWriterSize` | 2.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `reflect.mapassign_faststr0` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 334.65GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 202.77GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 202.11GB |
| 4 | `experiment/local.topologicalSort` | 133.78GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 123.07GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 105.22GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 64.13GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 56.27GB |
| 9 | `reflect.growslice` | 31.91GB |
| 10 | `segmentio/kafka-go.makePartitions` | 31.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/138 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 136/138 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 22.69MB | 136/138 | `█████████░░░░░░ 61%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/138 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/138 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/138 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/138 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.21MB | 70/138 | `████░░░░░░░░░░░ 33%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.72MB | 7/138 | `████░░░░░░░░░░░ 31%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 36/138 | `████░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 60.44GB | 131/138 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 59.34GB | 127/138 | `██████████████░ 98%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 34.97GB | 133/138 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 34.96GB | 133/138 | `████████░░░░░░░ 57%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.8GB | 129/138 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.41GB | 83/138 | `██████░░░░░░░░░ 42%` |
| 7 | `experiment/local.topologicalSort` | 25.15GB | 115/138 | `██████░░░░░░░░░ 41%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/138 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.growslice` | 22.41GB | 46/138 | `█████░░░░░░░░░░ 37%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/138 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
