# Overview: prod
*Last updated: 2026-05-16 16:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T16:02 (44 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,254 | avg: 16,220 | max: 84,644 | trend: decreasing (-112.76/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 169.5MB | avg: 276.1MB | max: 1896.6MB | trend: decreasing (-3.34MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,254 | 14,097 | +157 | 16,220 | 84,644 | decreasing (-112.76/hr) |
| Heap InUse | 169.5MB | 109.5MB | +60.0MB | 276.1MB | 1896.6MB | decreasing (-3.34MB/hr) |
| Heap Sys | 3299.1MB | 3301.2MB | -2.1MB | 5049.1MB | 5842.7MB | |
| Heap Objects | 969,910 | 439,560 | +530350 | 1,095,028 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 34 | 16,782 | 286.9MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 11.14GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 5.03GB |
| 3 | `internal/evaluation.mergeMetadata` | 4.02GB |
| 4 | `segmentio/kafka-go.makePartitions` | 2.68GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.52GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 2.44GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.76GB |
| 8 | `experiment/local.topologicalSort` | 1.65GB |
| 9 | `database/sql.convertAssignRows` | 1.51GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 36.96MB | 42/44 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 42/44 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/44 | `████████████░░░ 82%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/44 | `████████████░░░ 81%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/44 | `██████████░░░░░ 73%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/44 | `██████████░░░░░ 68%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/44 | `███████░░░░░░░░ 51%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/44 | `██████░░░░░░░░░ 44%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/44 | `██████░░░░░░░░░ 44%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/44 | `██████░░░░░░░░░ 43%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.35GB | 39/44 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 45.95GB | 33/44 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 25.93GB | 39/44 | `██████░░░░░░░░░ 41%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 25.75GB | 39/44 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 25.45GB | 23/44 | `██████░░░░░░░░░ 40%` |
| 6 | `fmt.(*buffer).writeString` | 24.63GB | 15/44 | `█████░░░░░░░░░░ 39%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.81GB | 38/44 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/44 | `████░░░░░░░░░░░ 31%` |
| 9 | `experiment/local.topologicalSort` | 18.92GB | 32/44 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/44 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.2x avg)
