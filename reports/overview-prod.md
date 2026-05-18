# Overview: prod
*Last updated: 2026-05-18 08:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T08:31 (125 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,176 | avg: 15,170 | max: 84,644 | trend: decreasing (-40.21/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 134.1MB | avg: 205.8MB | max: 1896.6MB | trend: decreasing (-2.53MB/hr))
```
▃▄▆▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,176 | 14,290 | -114 | 15,170 | 84,644 | decreasing (-40.21/hr) |
| Heap InUse | 134.1MB | 130.8MB | +3.3MB | 205.8MB | 1896.6MB | decreasing (-2.53MB/hr) |
| Heap Sys | 4699.4MB | 4699.4MB | +0.0MB | 4187.0MB | 5842.7MB | |
| Heap Objects | 614,464 | 531,910 | +82554 | 919,116 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 18 | 14,415 | 160.6MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.mapassign_faststr0` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 124.35GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 106.67GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.33GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 75.01GB |
| 5 | `experiment/local.topologicalSort` | 49.6GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 48.73GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 38.4GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 23.81GB |
| 9 | `segmentio/kafka-go.makePartitions` | 22.81GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.18GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/125 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 123/125 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/125 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.37MB | 123/125 | `████████░░░░░░░ 55%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/125 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/125 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/125 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.23MB | 57/125 | `████░░░░░░░░░░░ 33%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/125 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB | 29/125 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.44GB | 118/125 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 37.37GB | 114/125 | `██████████░░░░░ 68%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/125 | `██████░░░░░░░░░ 44%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.81GB | 116/125 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 22.26GB | 120/125 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 22.2GB | 120/125 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 20.37GB | 36/125 | `█████░░░░░░░░░░ 37%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/125 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/125 | `████░░░░░░░░░░░ 29%` |
| 10 | `experiment/local.topologicalSort` | 15.52GB | 102/125 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
