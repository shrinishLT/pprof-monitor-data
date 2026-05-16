# Overview: prod
*Last updated: 2026-05-17 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T04:31 (69 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,069 | avg: 15,495 | max: 84,644 | trend: decreasing (-109.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 165.3MB | avg: 231.7MB | max: 1896.6MB | trend: decreasing (-5.82MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,069 | 14,306 | -237 | 15,495 | 84,644 | decreasing (-109.30/hr) |
| Heap InUse | 165.3MB | 175.1MB | -9.8MB | 231.7MB | 1896.6MB | decreasing (-5.82MB/hr) |
| Heap Sys | 3765.6MB | 3589.3MB | +176.3MB | 4480.2MB | 5842.7MB | |
| Heap Objects | 1,180,841 | 1,073,042 | +107799 | 1,009,254 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 10 | 14,277 | 154.1MB | 184.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.45GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 26.12GB |
| 3 | `internal/evaluation.mergeMetadata` | 19.77GB |
| 4 | `segmentio/kafka-go.makePartitions` | 19.58GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 12.16GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 12.06GB |
| 7 | `reflect.unsafe_NewArray` | 10.11GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.18GB |
| 9 | `database/sql.convertAssignRows` | 8.03GB |
| 10 | `experiment/local.topologicalSort` | 7.88GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 67/69 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/69 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/69 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 27.2MB | 67/69 | `███████████░░░░ 74%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/69 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 21.1MB | 10/69 | `████████░░░░░░░ 57%` |
| 7 | `bytes.growSlice` | 16.79MB | 28/69 | `██████░░░░░░░░░ 45%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/69 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/69 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/69 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.72GB | 64/69 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.49GB | 58/69 | `█████████░░░░░░ 60%` |
| 3 | `reflect.growslice` | 25.45GB | 23/69 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/69 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/69 | `█████░░░░░░░░░░ 37%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 19.5GB | 63/69 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.81GB | 64/69 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.67GB | 64/69 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/69 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.12GB | 55/69 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
