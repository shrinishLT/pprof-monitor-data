# Overview: prod
*Last updated: 2026-05-17 19:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T19:02 (98 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,570 | avg: 15,403 | max: 84,644 | trend: decreasing (-47.81/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 179.9MB | avg: 219.8MB | max: 1896.6MB | trend: decreasing (-3.15MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,570 | 14,114 | +456 | 15,403 | 84,644 | decreasing (-47.81/hr) |
| Heap InUse | 179.9MB | 129.0MB | +50.9MB | 219.8MB | 1896.6MB | decreasing (-3.15MB/hr) |
| Heap Sys | 3575.6MB | 3576.6MB | -1.0MB | 4163.4MB | 5842.7MB | |
| Heap Objects | 931,352 | 587,959 | +343393 | 959,391 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 39 | 14,952 | 181.8MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `compress/flate.NewWriter` | 1.76MB |
| 7 | `bytes.growSlice` | 1.51MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 26.18GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 25.67GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 15.74GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 15.67GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 11.61GB |
| 6 | `experiment/local.topologicalSort` | 10.48GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.62GB |
| 8 | `segmentio/kafka-go.makePartitions` | 6.39GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 4.95GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 96/98 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/98 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/98 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 23.68MB | 96/98 | `█████████░░░░░░ 64%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/98 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/98 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/98 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/98 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/98 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/98 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.17GB | 91/98 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.4GB | 87/98 | `████████░░░░░░░ 56%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/98 | `██████░░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.13GB | 89/98 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/98 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.71GB | 93/98 | `█████░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.6GB | 93/98 | `█████░░░░░░░░░░ 33%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/98 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/98 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.13GB | 43/98 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
