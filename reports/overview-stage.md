# Overview: stage
*Last updated: 2026-05-20 04:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T04:00 (217 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,079 | avg: 14,341 | max: 28,205 | trend: INCREASING (+3.96/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 207.7MB | avg: 164.7MB | max: 732.9MB | trend: INCREASING (+0.52MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,079 | 14,068 | +11 | 14,341 | 28,205 | INCREASING (+3.96/hr) |
| Heap InUse | 207.7MB | 149.9MB | +57.8MB | 164.7MB | 732.9MB | INCREASING (+0.52MB/hr) |
| Heap Sys | 1779.8MB | 1779.8MB | +0.0MB | 1173.5MB | 1780.2MB | |
| Heap Objects | 1,037,741 | 699,389 | +338352 | 855,498 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 9 | 14,107 | 171.7MB | 207.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 177.85GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 115.46GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 114.79GB |
| 4 | `internal/evaluation.mergeMetadata` | 111.72GB |
| 5 | `reflect.unsafe_NewArray` | 76.85GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.4GB |
| 8 | `experiment/local.topologicalSort` | 57.12GB |
| 9 | `reflect.MakeSlice` | 42.83GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 215/217 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/217 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 13.58MB | 211/217 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.98MB | 29/217 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/217 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/217 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 214/217 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 206/217 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/217 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/217 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.27GB | 208/217 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 51.04GB | 210/217 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 50.81GB | 209/217 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 50.68GB | 204/217 | `████████░░░░░░░ 57%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 38.18GB | 193/217 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 38.16GB | 208/217 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.06GB | 206/217 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 25.8GB | 205/217 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 21.41GB | 206/217 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.62GB | 193/217 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
