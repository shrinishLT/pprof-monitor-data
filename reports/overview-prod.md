# Overview: prod
*Last updated: 2026-05-17 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T22:31 (105 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 15,319 | max: 84,644 | trend: decreasing (-47.93/hr))
```
▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 176.6MB | avg: 214.3MB | max: 1896.6MB | trend: decreasing (-3.15MB/hr))
```
▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,076 | -5 | 15,319 | 84,644 | decreasing (-47.93/hr) |
| Heap InUse | 176.6MB | 105.0MB | +71.6MB | 214.3MB | 1896.6MB | decreasing (-3.15MB/hr) |
| Heap Sys | 3885.6MB | 3885.4MB | +0.2MB | 4133.1MB | 5842.7MB | |
| Heap Objects | 1,332,529 | 400,413 | +932116 | 943,041 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 46 | 14,827 | 175.0MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.52MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.67GB |
| 2 | `internal/evaluation.mergeMetadata` | 33.22GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 19.99GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 19.95GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.42GB |
| 6 | `experiment/local.topologicalSort` | 13.35GB |
| 7 | `segmentio/kafka-go.makePartitions` | 10.48GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.72GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.78GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 6.29GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 103/105 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/105 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/105 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 22.66MB | 103/105 | `█████████░░░░░░ 61%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/105 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/105 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.37MB | 50/105 | `█████░░░░░░░░░░ 36%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/105 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/105 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/105 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.01GB | 98/105 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.55GB | 94/105 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/105 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.78GB | 96/105 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/105 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.79GB | 100/105 | `█████░░░░░░░░░░ 34%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.69GB | 100/105 | `█████░░░░░░░░░░ 34%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/105 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/105 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.58GB | 50/105 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
