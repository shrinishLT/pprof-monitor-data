# Overview: prod
*Last updated: 2026-05-17 03:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T03:01 (66 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,101 | avg: 15,554 | max: 84,644 | trend: decreasing (-113.62/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 119.9MB | avg: 235.0MB | max: 1896.6MB | trend: decreasing (-6.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,101 | 14,219 | -118 | 15,554 | 84,644 | decreasing (-113.62/hr) |
| Heap InUse | 119.9MB | 118.5MB | +1.4MB | 235.0MB | 1896.6MB | decreasing (-6.02MB/hr) |
| Heap Sys | 3469.1MB | 3468.9MB | +0.2MB | 4518.1MB | 5842.7MB | |
| Heap Objects | 529,924 | 422,171 | +107753 | 1,012,154 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 7 | 14,313 | 151.9MB | 184.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 47.71GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 21.72GB |
| 3 | `internal/evaluation.mergeMetadata` | 17.66GB |
| 4 | `segmentio/kafka-go.makePartitions` | 17.55GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 10.9GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 10.8GB |
| 7 | `reflect.unsafe_NewArray` | 9.11GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.77GB |
| 9 | `experiment/local.topologicalSort` | 7.06GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.82GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 64/66 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/66 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/66 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 27.96MB | 64/66 | `███████████░░░░ 76%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/66 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 21.1MB | 10/66 | `████████░░░░░░░ 57%` |
| 7 | `bytes.growSlice` | 17.92MB | 26/66 | `███████░░░░░░░░ 48%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/66 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/66 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/66 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.6GB | 61/66 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 32.17GB | 55/66 | `█████████░░░░░░ 62%` |
| 3 | `reflect.growslice` | 25.45GB | 23/66 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/66 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/66 | `█████░░░░░░░░░░ 38%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 19.24GB | 60/66 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 19.15GB | 61/66 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 19.01GB | 61/66 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/66 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.44GB | 52/66 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
