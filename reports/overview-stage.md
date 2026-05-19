# Overview: stage
*Last updated: 2026-05-19 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T09:31 (180 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,384 | max: 28,205 | trend: INCREASING (+10.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 188.4MB | avg: 162.7MB | max: 732.9MB | trend: INCREASING (+0.76MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,067 | +7 | 14,384 | 28,205 | INCREASING (+10.44/hr) |
| Heap InUse | 188.4MB | 156.9MB | +31.5MB | 162.7MB | 732.9MB | INCREASING (+0.76MB/hr) |
| Heap Sys | 1771.5MB | 1771.4MB | +0.1MB | 1049.7MB | 1771.5MB | |
| Heap Objects | 1,184,451 | 795,003 | +389448 | 846,294 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 20 | 14,111 | 175.8MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 144.71GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.28GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.43GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.73GB |
| 5 | `reflect.unsafe_NewArray` | 62.57GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.14GB |
| 8 | `experiment/local.topologicalSort` | 52.02GB |
| 9 | `reflect.MakeSlice` | 34.72GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 178/180 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/180 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/180 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/180 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.64MB | 174/180 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/180 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/180 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/180 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 177/180 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 169/180 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 72.37GB | 171/180 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 38.45GB | 173/180 | `███████░░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 38.37GB | 167/180 | `███████░░░░░░░░ 53%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 38.25GB | 172/180 | `███████░░░░░░░░ 52%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 32.39GB | 156/180 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 31.29GB | 171/180 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.61GB | 169/180 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 19.51GB | 168/180 | `████░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 17.59GB | 169/180 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.1GB | 156/180 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
