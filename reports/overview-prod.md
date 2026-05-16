# Overview: prod
*Last updated: 2026-05-16 14:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T14:03 (40 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,411 | avg: 16,407 | max: 84,644 | trend: decreasing (-88.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 257.3MB | avg: 289.5MB | max: 1896.6MB | trend: stable (-0.05MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,411 | 14,389 | +22 | 16,407 | 84,644 | decreasing (-88.43/hr) |
| Heap InUse | 257.3MB | 252.4MB | +4.9MB | 289.5MB | 1896.6MB | stable (-0.05MB/hr) |
| Heap Sys | 5840.8MB | 5840.7MB | +0.1MB | 5223.7MB | 5842.7MB | |
| Heap Objects | 1,068,177 | 1,170,442 | -102265 | 1,136,600 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 30 | 17,105 | 306.1MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bufio.NewWriterSize` | 3.03MB |
| 6 | `bytes.growSlice` | 3.02MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 81.34GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 79.21GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 49.46GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 49.23GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 35.95GB |
| 6 | `experiment/local.topologicalSort` | 32.5GB |
| 7 | `jackskj/carta.getUniqueId` | 27.88GB |
| 8 | `reflect.growslice` | 25.91GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.52GB |
| 10 | `fmt.(*buffer).writeString` | 21.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 39.79MB | 38/40 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 38/40 | `█████████████░░ 92%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/40 | `███████████░░░░ 76%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/40 | `███████████░░░░ 75%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/40 | `██████████░░░░░ 72%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/40 | `██████████░░░░░ 67%` |
| 7 | `bytes.growSlice` | 19.45MB | 23/40 | `███████░░░░░░░░ 48%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/40 | `██████░░░░░░░░░ 41%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/40 | `██████░░░░░░░░░ 41%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/40 | `██████░░░░░░░░░ 40%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 68.4GB | 35/40 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 51.89GB | 29/40 | `███████████░░░░ 75%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 28.69GB | 35/40 | `██████░░░░░░░░░ 41%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 28.5GB | 35/40 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 25.45GB | 23/40 | `█████░░░░░░░░░░ 37%` |
| 6 | `fmt.(*buffer).writeString` | 24.63GB | 15/40 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 23.87GB | 34/40 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 20.74GB | 29/40 | `████░░░░░░░░░░░ 30%` |
| 9 | `jackskj/carta.getUniqueId` | 19.62GB | 17/40 | `████░░░░░░░░░░░ 28%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/40 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.2x avg)
