# Overview: prod
*Last updated: 2026-05-17 01:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T01:31 (63 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,097 | avg: 15,599 | max: 84,644 | trend: decreasing (-121.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.3MB | avg: 239.5MB | max: 1896.6MB | trend: decreasing (-6.03MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,097 | 14,067 | +30 | 15,599 | 84,644 | decreasing (-121.54/hr) |
| Heap InUse | 161.3MB | 168.6MB | -7.3MB | 239.5MB | 1896.6MB | decreasing (-6.03MB/hr) |
| Heap Sys | 3472.2MB | 3472.2MB | +0.0MB | 4568.1MB | 5842.7MB | |
| Heap Objects | 953,200 | 1,222,991 | -269791 | 1,034,894 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 4 | 14,089 | 160.1MB | 168.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.growslice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 44.01GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 20.05GB |
| 3 | `segmentio/kafka-go.makePartitions` | 15.46GB |
| 4 | `internal/evaluation.mergeMetadata` | 14.59GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 9.01GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.94GB |
| 7 | `reflect.unsafe_NewArray` | 8.07GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.8GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.28GB |
| 10 | `database/sql.convertAssignRows` | 6.07GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 61/63 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/63 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/63 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 28.79MB | 61/63 | `███████████░░░░ 78%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/63 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/63 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/63 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/63 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/63 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/63 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.81GB | 58/63 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 33.03GB | 52/63 | `█████████░░░░░░ 63%` |
| 3 | `reflect.growslice` | 25.45GB | 23/63 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/63 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/63 | `█████░░░░░░░░░░ 37%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.59GB | 58/63 | `█████░░░░░░░░░░ 37%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 19.45GB | 58/63 | `█████░░░░░░░░░░ 37%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.11GB | 57/63 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/63 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.84GB | 49/63 | `████░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
