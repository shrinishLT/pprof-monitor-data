# Overview: stage
*Last updated: 2026-05-19 19:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T19:30 (200 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,377 | avg: 14,361 | max: 28,205 | trend: INCREASING (+6.40/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.3MB | avg: 164.5MB | max: 732.9MB | trend: INCREASING (+0.65MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▂▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,377 | 14,320 | +57 | 14,361 | 28,205 | INCREASING (+6.40/hr) |
| Heap InUse | 172.3MB | 175.5MB | -3.2MB | 164.5MB | 732.9MB | INCREASING (+0.65MB/hr) |
| Heap Sys | 1777.5MB | 1776.8MB | +0.7MB | 1122.1MB | 1777.5MB | |
| Heap Objects | 721,434 | 909,718 | -188284 | 857,547 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 40 | 14,134 | 178.4MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 4.86MB |
| 6 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.08MB |
| 10 | `experiment/local.topologicalSort` | 2.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 162.63GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 110.31GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 109.51GB |
| 4 | `internal/evaluation.mergeMetadata` | 106.59GB |
| 5 | `reflect.unsafe_NewArray` | 70.29GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.4GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 55.68GB |
| 8 | `experiment/local.topologicalSort` | 54.5GB |
| 9 | `reflect.MakeSlice` | 39.06GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 198/200 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/200 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/200 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.2MB | 194/200 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/200 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/200 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 197/200 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 189/200 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/200 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/200 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 80.93GB | 191/200 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 45.6GB | 193/200 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 45.37GB | 192/200 | `████████░░░░░░░ 56%` |
| 4 | `internal/evaluation.mergeMetadata` | 45.37GB | 187/200 | `████████░░░░░░░ 56%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 35.75GB | 176/200 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 34.99GB | 191/200 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.27GB | 189/200 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 23.08GB | 188/200 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 19.64GB | 189/200 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.56GB | 176/200 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
