# Overview: prod
*Last updated: 2026-05-16 12:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T12:31 (37 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,203 | avg: 16,574 | max: 84,644 | trend: decreasing (-52.94/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 209.7MB | avg: 293.6MB | max: 1896.6MB | trend: INCREASING (+1.36MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,203 | 14,231 | -28 | 16,574 | 84,644 | decreasing (-52.94/hr) |
| Heap InUse | 209.7MB | 304.2MB | -94.5MB | 293.6MB | 1896.6MB | INCREASING (+1.36MB/hr) |
| Heap Sys | 5840.7MB | 5840.6MB | +0.1MB | 5173.7MB | 5842.7MB | |
| Heap Objects | 616,241 | 1,660,821 | -1044580 | 1,151,801 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 27 | 17,413 | 313.6MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.(*compressor).initDeflate` | 2.14MB |
| 8 | `bufio.NewReaderSize` | 2.04MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 77.93GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 69.73GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 47.38GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 47.13GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 31.69GB |
| 6 | `experiment/local.topologicalSort` | 31.1GB |
| 7 | `jackskj/carta.getUniqueId` | 27.41GB |
| 8 | `reflect.growslice` | 25.58GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.48GB |
| 10 | `fmt.(*buffer).writeString` | 21.77GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 38.05MB | 35/37 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 35/37 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/37 | `████████████░░░ 80%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/37 | `███████████░░░░ 78%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/37 | `███████████░░░░ 75%` |
| 6 | `bytes.growSlice` | 20.92MB | 21/37 | `████████░░░░░░░ 54%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/37 | `██████░░░░░░░░░ 43%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/37 | `██████░░░░░░░░░ 43%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/37 | `█████░░░░░░░░░░ 39%` |
| 10 | `reflect.growslice` | 11.07MB | 2/37 | `████░░░░░░░░░░░ 29%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.51GB | 32/37 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 48.59GB | 26/37 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 26.79GB | 32/37 | `█████░░░░░░░░░░ 39%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 26.61GB | 32/37 | `█████░░░░░░░░░░ 39%` |
| 5 | `reflect.growslice` | 25.39GB | 20/37 | `█████░░░░░░░░░░ 37%` |
| 6 | `fmt.(*buffer).writeString` | 25.3GB | 12/37 | `█████░░░░░░░░░░ 37%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 22.75GB | 31/37 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 19.42GB | 26/37 | `████░░░░░░░░░░░ 28%` |
| 9 | `jackskj/carta.getUniqueId` | 17.86GB | 14/37 | `███░░░░░░░░░░░░ 26%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.86GB | 25/37 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.1x avg)
