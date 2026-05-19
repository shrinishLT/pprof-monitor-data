# Overview: stage
*Last updated: 2026-05-20 03:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T03:30 (216 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,342 | max: 28,205 | trend: INCREASING (+4.09/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 149.9MB | avg: 164.5MB | max: 732.9MB | trend: INCREASING (+0.52MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,064 | +4 | 14,342 | 28,205 | INCREASING (+4.09/hr) |
| Heap InUse | 149.9MB | 190.1MB | -40.2MB | 164.5MB | 732.9MB | INCREASING (+0.52MB/hr) |
| Heap Sys | 1779.8MB | 1779.8MB | +0.0MB | 1170.7MB | 1780.2MB | |
| Heap Objects | 699,389 | 1,193,094 | -493705 | 854,655 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 8 | 14,110 | 167.2MB | 204.5MB |

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
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 176.95GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 115.45GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 114.78GB |
| 4 | `internal/evaluation.mergeMetadata` | 111.7GB |
| 5 | `reflect.unsafe_NewArray` | 76.45GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.39GB |
| 8 | `experiment/local.topologicalSort` | 57.11GB |
| 9 | `reflect.MakeSlice` | 42.61GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 214/216 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/216 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 13.56MB | 210/216 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.98MB | 29/216 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/216 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/216 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 213/216 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 205/216 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/216 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/216 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 87.84GB | 207/216 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 50.74GB | 209/216 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 50.5GB | 208/216 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 50.38GB | 203/216 | `████████░░░░░░░ 57%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 38.05GB | 192/216 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 37.97GB | 207/216 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.9GB | 205/216 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 25.64GB | 204/216 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 21.31GB | 205/216 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.56GB | 192/216 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
