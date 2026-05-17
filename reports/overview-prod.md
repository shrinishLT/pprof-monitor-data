# Overview: prod
*Last updated: 2026-05-17 23:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T23:01 (106 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,221 | avg: 15,308 | max: 84,644 | trend: decreasing (-47.74/hr))
```
▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 171.2MB | avg: 213.9MB | max: 1896.6MB | trend: decreasing (-3.11MB/hr))
```
▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,221 | 14,071 | +150 | 15,308 | 84,644 | decreasing (-47.74/hr) |
| Heap InUse | 171.2MB | 176.6MB | -5.4MB | 213.9MB | 1896.6MB | decreasing (-3.11MB/hr) |
| Heap Sys | 3885.3MB | 3885.6MB | -0.3MB | 4130.8MB | 5842.7MB | |
| Heap Objects | 1,007,529 | 1,332,529 | -325000 | 943,650 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 47 | 14,814 | 174.9MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 2.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.7GB |
| 2 | `internal/evaluation.mergeMetadata` | 33.5GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 20.15GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 20.1GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.43GB |
| 6 | `experiment/local.topologicalSort` | 13.44GB |
| 7 | `segmentio/kafka-go.makePartitions` | 11.11GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.8GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.79GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 6.34GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 104/106 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/106 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/106 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 22.52MB | 104/106 | `█████████░░░░░░ 61%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/106 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/106 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.14MB | 51/106 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/106 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/106 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/106 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.93GB | 99/106 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.59GB | 95/106 | `████████░░░░░░░ 58%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/106 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.76GB | 97/106 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/106 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.81GB | 101/106 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.72GB | 101/106 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/106 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/106 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.52GB | 51/106 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
