# Overview: prod
*Last updated: 2026-05-16 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T20:03 (52 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,109 | avg: 15,915 | max: 84,644 | trend: decreasing (-127.68/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 111.4MB | avg: 258.5MB | max: 1896.6MB | trend: decreasing (-5.50MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,109 | 14,146 | -37 | 15,915 | 84,644 | decreasing (-127.68/hr) |
| Heap InUse | 111.4MB | 173.2MB | -61.8MB | 258.5MB | 1896.6MB | decreasing (-5.50MB/hr) |
| Heap Sys | 3471.2MB | 3470.8MB | +0.4MB | 4799.9MB | 5842.7MB | |
| Heap Objects | 388,750 | 1,170,766 | -782016 | 1,061,199 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 42 | 16,297 | 263.0MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.04MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `bufio.NewReaderSize` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 26.51GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 12.03GB |
| 3 | `internal/evaluation.mergeMetadata` | 10.89GB |
| 4 | `segmentio/kafka-go.makePartitions` | 7.96GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 6.78GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 6.71GB |
| 7 | `experiment/local.topologicalSort` | 4.42GB |
| 8 | `reflect.unsafe_NewArray` | 4.28GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.09GB |
| 10 | `database/sql.convertAssignRows` | 3.64GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 50/52 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 32.71MB | 50/52 | `█████████████░░ 89%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/52 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/52 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/52 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/52 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/52 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/52 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/52 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/52 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.39GB | 47/52 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 38.38GB | 41/52 | `██████████░░░░░ 69%` |
| 3 | `reflect.growslice` | 25.45GB | 23/52 | `██████░░░░░░░░░ 45%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/52 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 22.28GB | 47/52 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 22.12GB | 47/52 | `█████░░░░░░░░░░ 39%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 19.71GB | 46/52 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/52 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/52 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 16.05GB | 39/52 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
