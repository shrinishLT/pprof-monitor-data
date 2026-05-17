# Overview: prod
*Last updated: 2026-05-17 13:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T13:01 (86 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,415 | avg: 15,516 | max: 84,644 | trend: decreasing (-52.48/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 140.8MB | avg: 227.8MB | max: 1896.6MB | trend: decreasing (-3.37MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,415 | 15,825 | -1410 | 15,516 | 84,644 | decreasing (-52.48/hr) |
| Heap InUse | 140.8MB | 213.0MB | -72.2MB | 227.8MB | 1896.6MB | decreasing (-3.37MB/hr) |
| Heap Sys | 2586.7MB | 1906.5MB | +680.2MB | 4335.0MB | 5842.7MB | |
| Heap Objects | 384,274 | 912,296 | -528022 | 989,093 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 27 | 15,112 | 190.5MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 6 | `bytes.growSlice` | 2.8MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.01MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 40.65GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 24.54GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 24.5GB |
| 4 | `experiment/local.topologicalSort` | 16.34GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 15.64GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.78GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 7.68GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 4.76GB |
| 9 | `fmt.Sprintf` | 3.59GB |
| 10 | `reflect.growslice` | 2.78GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 84/86 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/86 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/86 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.73MB | 84/86 | `██████████░░░░░ 70%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/86 | `███████░░░░░░░░ 50%` |
| 6 | `bytes.growSlice` | 15.32MB | 41/86 | `██████░░░░░░░░░ 41%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.96MB | 19/86 | `█████░░░░░░░░░░ 38%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/86 | `█████░░░░░░░░░░ 36%` |
| 9 | `database/sql.convertAssignRows` | 13.33MB | 6/86 | `█████░░░░░░░░░░ 36%` |
| 10 | `crypto/tls.Client` | 13.01MB | 3/86 | `█████░░░░░░░░░░ 35%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.83GB | 79/86 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.87GB | 75/86 | `████████░░░░░░░ 53%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/86 | `██████░░░░░░░░░ 41%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 23.37GB | 77/86 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/86 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.53GB | 81/86 | `████░░░░░░░░░░░ 32%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.4GB | 81/86 | `████░░░░░░░░░░░ 31%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/86 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.1GB | 4/86 | `████░░░░░░░░░░░ 27%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.88GB | 31/86 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
