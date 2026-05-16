# Overview: prod
*Last updated: 2026-05-16 17:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T17:31 (47 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,143 | avg: 16,087 | max: 84,644 | trend: decreasing (-124.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 243.6MB | avg: 270.1MB | max: 1896.6MB | trend: decreasing (-4.15MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,143 | 14,098 | +45 | 16,087 | 84,644 | decreasing (-124.36/hr) |
| Heap InUse | 243.6MB | 162.5MB | +81.1MB | 270.1MB | 1896.6MB | decreasing (-4.15MB/hr) |
| Heap Sys | 3474.3MB | 3298.2MB | +176.1MB | 4941.1MB | 5842.7MB | |
| Heap Objects | 1,182,039 | 1,025,043 | +156996 | 1,086,672 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 37 | 16,567 | 278.4MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.13MB |
| 3 | `database/sql.convertAssignRows` | 14.5MB |
| 4 | `runtime.mallocgc` | 10.01MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.5MB |
| 8 | `dotlapse-event-service/project.FilterProjectsByTags` | 2.54MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 20.3GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 9.29GB |
| 3 | `internal/evaluation.mergeMetadata` | 5.91GB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.64GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.7GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.58GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.13GB |
| 8 | `database/sql.convertAssignRows` | 2.74GB |
| 9 | `reflect.unsafe_NewArray` | 2.46GB |
| 10 | `experiment/local.topologicalSort` | 2.4GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 45/47 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 35.16MB | 45/47 | `██████████████░ 95%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/47 | `████████████░░░ 83%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.07MB | 3/47 | `████████████░░░ 82%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/47 | `████████████░░░ 81%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/47 | `██████████░░░░░ 69%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/47 | `███████░░░░░░░░ 51%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/47 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/47 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/47 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.1GB | 42/47 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 42.56GB | 36/47 | `██████████░░░░░ 72%` |
| 3 | `reflect.growslice` | 25.45GB | 23/47 | `██████░░░░░░░░░ 43%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/47 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 24.32GB | 42/47 | `██████░░░░░░░░░ 41%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 24.15GB | 42/47 | `██████░░░░░░░░░ 40%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 20.77GB | 41/47 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/47 | `████░░░░░░░░░░░ 33%` |
| 9 | `experiment/local.topologicalSort` | 17.49GB | 35/47 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/47 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
