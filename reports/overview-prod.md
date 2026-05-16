# Overview: prod
*Last updated: 2026-05-17 00:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T00:31 (61 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,072 | avg: 15,649 | max: 84,644 | trend: decreasing (-123.79/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 163.5MB | avg: 241.9MB | max: 1896.6MB | trend: decreasing (-6.14MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,072 | 14,121 | -49 | 15,649 | 84,644 | decreasing (-123.79/hr) |
| Heap InUse | 163.5MB | 147.0MB | +16.5MB | 241.9MB | 1896.6MB | decreasing (-6.14MB/hr) |
| Heap Sys | 3472.2MB | 3471.9MB | +0.3MB | 4604.0MB | 5842.7MB | |
| Heap Objects | 1,166,939 | 857,101 | +309838 | 1,033,150 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 2 | 14,096 | 155.2MB | 163.5MB |

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
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `compress/flate.(*huffmanEncoder).generate` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 41.3GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.8GB |
| 3 | `internal/evaluation.mergeMetadata` | 14.2GB |
| 4 | `segmentio/kafka-go.makePartitions` | 14.03GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.79GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.72GB |
| 7 | `reflect.unsafe_NewArray` | 7.34GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.38GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.83GB |
| 10 | `experiment/local.topologicalSort` | 5.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 59/61 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/61 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/61 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 29.4MB | 59/61 | `████████████░░░ 80%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/61 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/61 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/61 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/61 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/61 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/61 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.13GB | 56/61 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 33.78GB | 50/61 | `█████████░░░░░░ 64%` |
| 3 | `reflect.growslice` | 25.45GB | 23/61 | `███████░░░░░░░░ 48%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/61 | `███████░░░░░░░░ 47%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 19.98GB | 56/61 | `█████░░░░░░░░░░ 38%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 19.83GB | 56/61 | `█████░░░░░░░░░░ 38%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/61 | `█████░░░░░░░░░░ 37%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.1GB | 55/61 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/61 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 14.01GB | 48/61 | `████░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
