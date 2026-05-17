# Overview: prod
*Last updated: 2026-05-17 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T13:31 (87 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,399 | avg: 15,504 | max: 84,644 | trend: decreasing (-52.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 159.6MB | avg: 227.0MB | max: 1896.6MB | trend: decreasing (-3.36MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,399 | 14,415 | -16 | 15,504 | 84,644 | decreasing (-52.44/hr) |
| Heap InUse | 159.6MB | 140.8MB | +18.8MB | 227.0MB | 1896.6MB | decreasing (-3.36MB/hr) |
| Heap Sys | 2743.1MB | 2586.7MB | +156.4MB | 4316.7MB | 5842.7MB | |
| Heap Objects | 655,288 | 384,274 | +271014 | 985,256 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 28 | 15,086 | 189.4MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.49MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 43.87GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 26.45GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 26.44GB |
| 4 | `experiment/local.topologicalSort` | 17.62GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 15.65GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.66GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 9.48GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 8.29GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 4.26GB |
| 10 | `fmt.Sprintf` | 3.92GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 85/87 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/87 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/87 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.64MB | 85/87 | `██████████░░░░░ 69%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/87 | `███████░░░░░░░░ 50%` |
| 6 | `bytes.growSlice` | 15.11MB | 42/87 | `██████░░░░░░░░░ 41%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.96MB | 19/87 | `█████░░░░░░░░░░ 38%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/87 | `█████░░░░░░░░░░ 36%` |
| 9 | `database/sql.convertAssignRows` | 13.33MB | 6/87 | `█████░░░░░░░░░░ 36%` |
| 10 | `crypto/tls.Client` | 13.01MB | 3/87 | `█████░░░░░░░░░░ 35%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.23GB | 80/87 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.04GB | 76/87 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/87 | `██████░░░░░░░░░ 42%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 23.13GB | 78/87 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/87 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.63GB | 82/87 | `████░░░░░░░░░░░ 32%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.5GB | 82/87 | `████░░░░░░░░░░░ 32%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/87 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/87 | `████░░░░░░░░░░░ 27%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.81GB | 32/87 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
