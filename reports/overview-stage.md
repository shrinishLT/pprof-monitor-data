# Overview: stage
*Last updated: 2026-05-21 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T04:31 (266 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,079 | avg: 14,303 | max: 28,205 | trend: INCREASING (+0.72/hr))
```
▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▁▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 158.6MB | avg: 167.1MB | max: 732.9MB | trend: stable (+0.36MB/hr))
```
▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,079 | 14,073 | +6 | 14,303 | 28,205 | INCREASING (+0.72/hr) |
| Heap InUse | 158.6MB | 162.3MB | -3.7MB | 167.1MB | 732.9MB | stable (+0.36MB/hr) |
| Heap Sys | 1792.0MB | 1791.6MB | +0.4MB | 1286.2MB | 1792.1MB | |
| Heap Objects | 776,487 | 855,177 | -78690 | 866,207 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 10 | 14,082 | 169.0MB | 203.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 222.03GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 133.53GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 132.77GB |
| 4 | `internal/evaluation.mergeMetadata` | 129.26GB |
| 5 | `reflect.unsafe_NewArray` | 95.8GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 67.47GB |
| 8 | `experiment/local.topologicalSort` | 66.11GB |
| 9 | `reflect.MakeSlice` | 53.51GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 264/266 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/266 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.42MB | 260/266 | `█████░░░░░░░░░░ 39%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/266 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/266 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/266 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 263/266 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/266 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 255/266 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/266 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 109.64GB | 257/266 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 64.93GB | 259/266 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 64.65GB | 258/266 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 64.19GB | 253/266 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 47.37GB | 257/266 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.96GB | 242/266 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.12GB | 255/266 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 32.7GB | 254/266 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 26.57GB | 255/266 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.01GB | 242/266 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
