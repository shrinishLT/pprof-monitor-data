# Overview: stage
*Last updated: 2026-05-19 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T20:02 (201 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,089 | avg: 14,360 | max: 28,205 | trend: INCREASING (+6.22/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 193.8MB | avg: 164.7MB | max: 732.9MB | trend: INCREASING (+0.65MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,089 | 14,377 | -288 | 14,360 | 28,205 | INCREASING (+6.22/hr) |
| Heap InUse | 193.8MB | 172.3MB | +21.5MB | 164.7MB | 732.9MB | INCREASING (+0.65MB/hr) |
| Heap Sys | 1778.2MB | 1777.5MB | +0.7MB | 1125.3MB | 1778.2MB | |
| Heap Objects | 1,190,738 | 721,434 | +469304 | 859,205 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 41 | 14,133 | 178.7MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.02MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 163.56GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 110.54GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 109.74GB |
| 4 | `internal/evaluation.mergeMetadata` | 106.83GB |
| 5 | `reflect.unsafe_NewArray` | 70.71GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.4GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 55.8GB |
| 8 | `experiment/local.topologicalSort` | 54.63GB |
| 9 | `reflect.MakeSlice` | 39.31GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 199/201 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/201 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/201 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.22MB | 195/201 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/201 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/201 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 198/201 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 190/201 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/201 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/201 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 81.36GB | 192/201 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 45.93GB | 194/201 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 45.71GB | 193/201 | `████████░░░░░░░ 56%` |
| 4 | `internal/evaluation.mergeMetadata` | 45.69GB | 188/201 | `████████░░░░░░░ 56%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 35.9GB | 177/201 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 35.18GB | 192/201 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.45GB | 190/201 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 23.25GB | 189/201 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 19.75GB | 190/201 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.63GB | 177/201 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
