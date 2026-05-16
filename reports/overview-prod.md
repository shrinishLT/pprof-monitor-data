# Overview: prod
*Last updated: 2026-05-16 16:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T16:32 (45 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,162 | avg: 16,175 | max: 84,644 | trend: decreasing (-117.34/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 139.5MB | avg: 273.1MB | max: 1896.6MB | trend: decreasing (-3.91MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,162 | 14,254 | -92 | 16,175 | 84,644 | decreasing (-117.34/hr) |
| Heap InUse | 139.5MB | 169.5MB | -30.0MB | 273.1MB | 1896.6MB | decreasing (-3.91MB/hr) |
| Heap Sys | 3298.0MB | 3299.1MB | -1.1MB | 5010.2MB | 5842.7MB | |
| Heap Objects | 685,271 | 969,910 | -284639 | 1,085,922 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 35 | 16,707 | 282.7MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 3.02MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.96GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.79GB |
| 3 | `internal/evaluation.mergeMetadata` | 4.93GB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.31GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 3.07GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 2.98GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.33GB |
| 8 | `database/sql.convertAssignRows` | 2.03GB |
| 9 | `experiment/local.topologicalSort` | 1.99GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.9GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 43/45 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 36.33MB | 43/45 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/45 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/45 | `████████████░░░ 81%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/45 | `███████████░░░░ 73%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.43MB | 8/45 | `██████████░░░░░ 69%` |
| 7 | `bytes.growSlice` | 18.91MB | 24/45 | `███████░░░░░░░░ 51%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/45 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/45 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/45 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 61.17GB | 40/45 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 44.74GB | 34/45 | `██████████░░░░░ 73%` |
| 3 | `reflect.growslice` | 25.45GB | 23/45 | `██████░░░░░░░░░ 41%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 25.36GB | 40/45 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 25.19GB | 40/45 | `██████░░░░░░░░░ 41%` |
| 6 | `fmt.(*buffer).writeString` | 24.63GB | 15/45 | `██████░░░░░░░░░ 40%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.42GB | 39/45 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 19.62GB | 17/45 | `████░░░░░░░░░░░ 32%` |
| 9 | `experiment/local.topologicalSort` | 18.41GB | 33/45 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/45 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.2x avg)
