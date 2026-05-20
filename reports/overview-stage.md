# Overview: stage
*Last updated: 2026-05-20 16:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T16:00 (241 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,129 | avg: 14,321 | max: 28,205 | trend: INCREASING (+1.99/hr))
```
▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 224.8MB | avg: 166.9MB | max: 732.9MB | trend: stable (+0.48MB/hr))
```
▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,129 | 14,257 | -128 | 14,321 | 28,205 | INCREASING (+1.99/hr) |
| Heap InUse | 224.8MB | 203.7MB | +21.1MB | 166.9MB | 732.9MB | stable (+0.48MB/hr) |
| Heap Sys | 1783.9MB | 1783.5MB | +0.4MB | 1234.1MB | 1783.9MB | |
| Heap Objects | 1,446,727 | 1,256,996 | +189731 | 867,495 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 33 | 14,130 | 183.1MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 3.55MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 199.4GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 123.3GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 122.53GB |
| 4 | `internal/evaluation.mergeMetadata` | 119.31GB |
| 5 | `reflect.unsafe_NewArray` | 86.01GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 62.17GB |
| 8 | `experiment/local.topologicalSort` | 61.02GB |
| 9 | `reflect.MakeSlice` | 48.0GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 239/241 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/241 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.04MB | 235/241 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.37MB | 31/241 | `█████░░░░░░░░░░ 33%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/241 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/241 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 238/241 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/241 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 230/241 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/241 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.69GB | 232/241 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 58.09GB | 234/241 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 57.84GB | 233/241 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 57.54GB | 228/241 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 42.66GB | 232/241 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.19GB | 217/241 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.64GB | 230/241 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 29.3GB | 229/241 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 23.93GB | 230/241 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.37GB | 217/241 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
