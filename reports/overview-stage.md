# Overview: stage
*Last updated: 2026-05-20 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T01:30 (212 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,346 | max: 28,205 | trend: INCREASING (+4.53/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 188.1MB | avg: 164.2MB | max: 732.9MB | trend: INCREASING (+0.53MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,346 | 28,205 | INCREASING (+4.53/hr) |
| Heap InUse | 188.1MB | 128.0MB | +60.1MB | 164.2MB | 732.9MB | INCREASING (+0.53MB/hr) |
| Heap Sys | 1779.2MB | 1780.2MB | -1.0MB | 1159.3MB | 1780.2MB | |
| Heap Objects | 1,202,681 | 349,070 | +853611 | 852,480 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 4 | 14,068 | 156.6MB | 188.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 173.4GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 112.55GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 111.85GB |
| 4 | `internal/evaluation.mergeMetadata` | 108.85GB |
| 5 | `reflect.unsafe_NewArray` | 74.92GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 56.89GB |
| 8 | `experiment/local.topologicalSort` | 55.69GB |
| 9 | `reflect.MakeSlice` | 41.76GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 210/212 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/212 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 13.48MB | 206/212 | `█████░░░░░░░░░░ 36%` |
| 4 | `bytes.growSlice` | 13.35MB | 28/212 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/212 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/212 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 209/212 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 201/212 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/212 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/212 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 86.11GB | 203/212 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 49.49GB | 205/212 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 49.26GB | 204/212 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 49.16GB | 199/212 | `████████░░░░░░░ 57%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 37.51GB | 188/212 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 37.23GB | 203/212 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.27GB | 201/212 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 25.02GB | 200/212 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 20.89GB | 201/212 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.33GB | 188/212 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
