# Overview: prod
*Last updated: 2026-05-17 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T18:31 (97 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,114 | avg: 15,412 | max: 84,644 | trend: decreasing (-48.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 129.0MB | avg: 220.2MB | max: 1896.6MB | trend: decreasing (-3.20MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,114 | 14,446 | -332 | 15,412 | 84,644 | decreasing (-48.23/hr) |
| Heap InUse | 129.0MB | 174.1MB | -45.1MB | 220.2MB | 1896.6MB | decreasing (-3.20MB/hr) |
| Heap Sys | 3576.6MB | 3576.1MB | +0.5MB | 4169.5MB | 5842.7MB | |
| Heap Objects | 587,959 | 917,442 | -329483 | 959,680 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 38 | 14,962 | 181.9MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 25.64GB |
| 2 | `internal/evaluation.mergeMetadata` | 25.44GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 15.32GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 15.23GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 11.59GB |
| 6 | `experiment/local.topologicalSort` | 10.18GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.46GB |
| 8 | `segmentio/kafka-go.makePartitions` | 5.76GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 4.81GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 95/97 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/97 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/97 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 23.84MB | 95/97 | `█████████░░░░░░ 65%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/97 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/97 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 13.61MB | 49/97 | `█████░░░░░░░░░░ 37%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/97 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.03MB | 23/97 | `████░░░░░░░░░░░ 32%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/97 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.46GB | 90/97 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.44GB | 86/97 | `████████░░░░░░░ 56%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/97 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 88/97 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/97 | `█████░░░░░░░░░░ 38%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.74GB | 92/97 | `█████░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.62GB | 92/97 | `█████░░░░░░░░░░ 33%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/97 | `████░░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/97 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.26GB | 42/97 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
