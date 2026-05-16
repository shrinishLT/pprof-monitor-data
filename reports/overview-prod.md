# Overview: prod
*Last updated: 2026-05-16 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T23:31 (59 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,098 | avg: 15,702 | max: 84,644 | trend: decreasing (-125.74/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 129.4MB | avg: 244.9MB | max: 1896.6MB | trend: decreasing (-6.17MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,098 | 14,081 | +17 | 15,702 | 84,644 | decreasing (-125.74/hr) |
| Heap InUse | 129.4MB | 177.8MB | -48.4MB | 244.9MB | 1896.6MB | decreasing (-6.17MB/hr) |
| Heap Sys | 3472.0MB | 3471.8MB | +0.2MB | 4642.4MB | 5842.7MB | |
| Heap Objects | 677,278 | 1,341,908 | -664630 | 1,033,866 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.41GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.5GB |
| 3 | `internal/evaluation.mergeMetadata` | 13.68GB |
| 4 | `segmentio/kafka-go.makePartitions` | 12.69GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.47GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.4GB |
| 7 | `reflect.unsafe_NewArray` | 6.69GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.94GB |
| 9 | `experiment/local.topologicalSort` | 5.5GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 57/59 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/59 | `████████████░░░ 83%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/59 | `████████████░░░ 82%` |
| 4 | `runtime.mallocgc` | 30.04MB | 57/59 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/59 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/59 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/59 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/59 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/59 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/59 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.59GB | 54/59 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 34.6GB | 48/59 | `█████████░░░░░░ 65%` |
| 3 | `reflect.growslice` | 25.45GB | 23/59 | `███████░░░░░░░░ 48%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/59 | `███████░░░░░░░░ 46%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.39GB | 54/59 | `█████░░░░░░░░░░ 38%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.24GB | 54/59 | `█████░░░░░░░░░░ 38%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/59 | `█████░░░░░░░░░░ 37%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.13GB | 53/59 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/59 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 14.37GB | 46/59 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
