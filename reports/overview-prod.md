# Overview: prod
*Last updated: 2026-05-17 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T08:01 (76 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,188 | avg: 15,416 | max: 84,644 | trend: decreasing (-93.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.6MB | avg: 226.5MB | max: 1896.6MB | trend: decreasing (-5.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,188 | 14,158 | +30 | 15,416 | 84,644 | decreasing (-93.36/hr) |
| Heap InUse | 161.6MB | 122.4MB | +39.2MB | 226.5MB | 1896.6MB | decreasing (-5.11MB/hr) |
| Heap Sys | 4130.9MB | 4130.6MB | +0.3MB | 4443.2MB | 5842.7MB | |
| Heap Objects | 881,436 | 490,485 | +390951 | 998,187 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 17 | 14,425 | 162.7MB | 211.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.unsafe_NewArray` | 3.52MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 93.89GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.78GB |
| 3 | `internal/evaluation.mergeMetadata` | 27.77GB |
| 4 | `segmentio/kafka-go.makePartitions` | 24.34GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.99GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 16.91GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 15.88GB |
| 8 | `database/sql.convertAssignRows` | 12.92GB |
| 9 | `reflect.unsafe_NewArray` | 12.6GB |
| 10 | `reflect.growslice` | 11.35GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 74/76 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/76 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/76 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/76 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 25.67MB | 74/76 | `██████████░░░░░ 70%` |
| 6 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/76 | `██████░░░░░░░░░ 45%` |
| 7 | `crypto/tls.Client` | 16.51MB | 2/76 | `██████░░░░░░░░░ 45%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/76 | `██████░░░░░░░░░ 44%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.93MB | 14/76 | `██████░░░░░░░░░ 43%` |
| 10 | `bytes.growSlice` | 15.36MB | 32/76 | `██████░░░░░░░░░ 41%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.59GB | 71/76 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.78GB | 65/76 | `████████░░░░░░░ 56%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/76 | `██████░░░░░░░░░ 45%` |
| 4 | `reflect.growslice` | 22.46GB | 29/76 | `██████░░░░░░░░░ 41%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 21.23GB | 70/76 | `█████░░░░░░░░░░ 38%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/76 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.45GB | 71/76 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.32GB | 71/76 | `█████░░░░░░░░░░ 33%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/76 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 13.03GB | 56/76 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
