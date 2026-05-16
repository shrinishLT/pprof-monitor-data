# Overview: prod
*Last updated: 2026-05-16 12:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T12:03 (36 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,231 | avg: 16,640 | max: 84,644 | trend: decreasing (-34.89/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 304.2MB | avg: 295.9MB | max: 1896.6MB | trend: INCREASING (+2.27MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,231 | 14,564 | -333 | 16,640 | 84,644 | decreasing (-34.89/hr) |
| Heap InUse | 304.2MB | 309.9MB | -5.7MB | 295.9MB | 1896.6MB | INCREASING (+2.27MB/hr) |
| Heap Sys | 5840.6MB | 5840.3MB | +0.3MB | 5155.2MB | 5842.7MB | |
| Heap Objects | 1,660,821 | 1,369,947 | +290874 | 1,166,678 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 26 | 17,536 | 317.6MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `reflect.unsafe_NewArray` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 77.17GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 68.19GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 46.95GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 46.65GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 30.98GB |
| 6 | `experiment/local.topologicalSort` | 30.78GB |
| 7 | `jackskj/carta.getUniqueId` | 27.09GB |
| 8 | `reflect.growslice` | 25.39GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.23GB |
| 10 | `fmt.(*buffer).writeString` | 21.62GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 37.4MB | 34/36 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 34/36 | `██████████████░ 97%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/36 | `████████████░░░ 81%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/36 | `████████████░░░ 80%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/36 | `███████████░░░░ 76%` |
| 6 | `bytes.growSlice` | 20.92MB | 21/36 | `████████░░░░░░░ 55%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/36 | `██████░░░░░░░░░ 44%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/36 | `██████░░░░░░░░░ 44%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/36 | `██████░░░░░░░░░ 40%` |
| 10 | `reflect.growslice` | 11.07MB | 2/36 | `████░░░░░░░░░░░ 29%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.44GB | 31/36 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 47.41GB | 25/36 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 26.12GB | 31/36 | `█████░░░░░░░░░░ 38%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 25.94GB | 31/36 | `█████░░░░░░░░░░ 38%` |
| 5 | `fmt.(*buffer).writeString` | 25.62GB | 11/36 | `█████░░░░░░░░░░ 37%` |
| 6 | `reflect.growslice` | 25.38GB | 19/36 | `█████░░░░░░░░░░ 37%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 22.46GB | 30/36 | `████░░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 18.95GB | 25/36 | `████░░░░░░░░░░░ 28%` |
| 9 | `jackskj/carta.getUniqueId` | 17.12GB | 13/36 | `███░░░░░░░░░░░░ 25%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.5GB | 24/36 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.1x avg)
