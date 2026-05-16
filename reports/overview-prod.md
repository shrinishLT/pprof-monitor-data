# Overview: prod
*Last updated: 2026-05-16 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T08:01 (29 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,166 | avg: 17,154 | max: 84,644 | trend: INCREASING (+198.65/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 253.2MB | avg: 304.9MB | max: 1896.6MB | trend: INCREASING (+8.71MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,166 | 14,420 | -254 | 17,154 | 84,644 | INCREASING (+198.65/hr) |
| Heap InUse | 253.2MB | 241.5MB | +11.7MB | 304.9MB | 1896.6MB | INCREASING (+8.71MB/hr) |
| Heap Sys | 5833.4MB | 5833.1MB | +0.3MB | 4989.9MB | 5833.4MB | |
| Heap Objects | 1,170,051 | 877,164 | +292887 | 1,194,055 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 19 | 18,650 | 339.4MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 9 | `reflect.unsafe_NewArray` | 1.52MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 61.51GB |
| 2 | `internal/evaluation.mergeMetadata` | 60.67GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 37.02GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 36.7GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.94GB |
| 6 | `experiment/local.topologicalSort` | 24.21GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.03GB |
| 8 | `reflect.growslice` | 13.83GB |
| 9 | `jackskj/carta.getUniqueId` | 13.63GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.19GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 38.68MB | 5/29 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 27/29 | `██████████████░ 94%` |
| 3 | `runtime.mallocgc` | 31.51MB | 27/29 | `████████████░░░ 81%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/29 | `███████████░░░░ 78%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/29 | `███████████░░░░ 77%` |
| 6 | `bytes.growSlice` | 26.33MB | 16/29 | `██████████░░░░░ 68%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/29 | `██████░░░░░░░░░ 42%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/29 | `██████░░░░░░░░░ 42%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/29 | `█████░░░░░░░░░░ 38%` |
| 10 | `bufio.NewReaderSize` | 11.82MB | 14/29 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.82GB | 24/29 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 38.37GB | 18/29 | `████████░░░░░░░ 56%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/29 | `██████░░░░░░░░░ 46%` |
| 4 | `reflect.growslice` | 28.63GB | 12/29 | `██████░░░░░░░░░ 42%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.18GB | 24/29 | `████░░░░░░░░░░░ 31%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.05GB | 24/29 | `████░░░░░░░░░░░ 31%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 20.15GB | 23/29 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 15.36GB | 18/29 | `███░░░░░░░░░░░░ 22%` |
| 9 | `jackskj/carta.getUniqueId` | 12.9GB | 6/29 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.75GB | 17/29 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.9x avg)
