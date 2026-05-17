# Overview: prod
*Last updated: 2026-05-18 03:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T03:01 (114 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,196 | avg: 15,234 | max: 84,644 | trend: decreasing (-45.66/hr))
```
▁▄▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 141.8MB | avg: 208.9MB | max: 1896.6MB | trend: decreasing (-2.98MB/hr))
```
▄▇▂▃▄▅█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,196 | 14,119 | +77 | 15,234 | 84,644 | decreasing (-45.66/hr) |
| Heap InUse | 141.8MB | 156.5MB | -14.7MB | 208.9MB | 1896.6MB | decreasing (-2.98MB/hr) |
| Heap Sys | 4698.8MB | 4698.5MB | +0.3MB | 4137.7MB | 5842.7MB | |
| Heap Objects | 718,086 | 911,999 | -193913 | 928,711 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 7 | 14,269 | 139.4MB | 156.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 62.79GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 60.3GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 37.82GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 37.8GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.57GB |
| 6 | `experiment/local.topologicalSort` | 25.05GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.04GB |
| 8 | `segmentio/kafka-go.makePartitions` | 15.77GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 11.93GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.79GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 112/114 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/114 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/114 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.52MB | 112/114 | `████████░░░░░░░ 58%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/114 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/114 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/114 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 13.0MB | 52/114 | `█████░░░░░░░░░░ 35%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/114 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.7MB | 24/114 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.09GB | 107/114 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.78GB | 103/114 | `█████████░░░░░░ 60%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/114 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.03GB | 105/114 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/114 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.48GB | 109/114 | `█████░░░░░░░░░░ 36%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.4GB | 109/114 | `█████░░░░░░░░░░ 36%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/114 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/114 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.64GB | 59/114 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
