# Overview: prod
*Last updated: 2026-05-17 00:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T00:03 (60 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,121 | avg: 15,675 | max: 84,644 | trend: decreasing (-124.74/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 147.0MB | avg: 243.2MB | max: 1896.6MB | trend: decreasing (-6.19MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,121 | 14,098 | +23 | 15,675 | 84,644 | decreasing (-124.74/hr) |
| Heap InUse | 147.0MB | 129.4MB | +17.6MB | 243.2MB | 1896.6MB | decreasing (-6.19MB/hr) |
| Heap Sys | 3471.9MB | 3472.0MB | -0.1MB | 4622.8MB | 5842.7MB | |
| Heap Objects | 857,101 | 677,278 | +179823 | 1,030,920 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 1 | 14,121 | 147.0MB | 147.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.52MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 3.5MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `database/sql.convertAssignRows` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.44GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.52GB |
| 3 | `internal/evaluation.mergeMetadata` | 13.83GB |
| 4 | `segmentio/kafka-go.makePartitions` | 13.47GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.57GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.5GB |
| 7 | `reflect.unsafe_NewArray` | 7.06GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.95GB |
| 9 | `experiment/local.topologicalSort` | 5.55GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 58/60 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/60 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/60 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 29.71MB | 58/60 | `████████████░░░ 81%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/60 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/60 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/60 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/60 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/60 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/60 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.33GB | 55/60 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 34.18GB | 49/60 | `█████████░░░░░░ 65%` |
| 3 | `reflect.growslice` | 25.45GB | 23/60 | `███████░░░░░░░░ 48%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/60 | `███████░░░░░░░░ 47%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 20.18GB | 55/60 | `█████░░░░░░░░░░ 38%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 20.03GB | 55/60 | `█████░░░░░░░░░░ 38%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/60 | `█████░░░░░░░░░░ 37%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.1GB | 54/60 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/60 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 14.19GB | 47/60 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
