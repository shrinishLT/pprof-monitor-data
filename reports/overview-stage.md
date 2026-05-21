# Overview: stage
*Last updated: 2026-05-21 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T13:31 (292 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,243 | avg: 14,290 | max: 28,205 | trend: stable (+0.08/hr))
```
▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂▃
```

**Heap InUse** (current: 198.0MB | avg: 167.6MB | max: 732.9MB | trend: stable (+0.29MB/hr))
```
▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,243 | 14,185 | +58 | 14,290 | 28,205 | stable (+0.08/hr) |
| Heap InUse | 198.0MB | 158.4MB | +39.6MB | 167.6MB | 732.9MB | stable (+0.29MB/hr) |
| Heap Sys | 1793.6MB | 1793.5MB | +0.1MB | 1331.4MB | 1793.6MB | |
| Heap Objects | 851,380 | 713,253 | +138127 | 862,142 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 36 | 14,141 | 171.7MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 5.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 3.76MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `experiment/local.topologicalSort` | 3.05MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.57MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 238.39GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 138.92GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 138.27GB |
| 4 | `internal/evaluation.mergeMetadata` | 134.55GB |
| 5 | `reflect.unsafe_NewArray` | 102.86GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.73GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.08GB |
| 8 | `experiment/local.topologicalSort` | 68.76GB |
| 9 | `reflect.MakeSlice` | 57.4GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 290/292 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/292 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.74MB | 286/292 | `██████░░░░░░░░░ 40%` |
| 4 | `bytes.growSlice` | 10.81MB | 37/292 | `████░░░░░░░░░░░ 29%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/292 | `████░░░░░░░░░░░ 28%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/292 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 289/292 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 281/292 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/292 | `███░░░░░░░░░░░░ 23%` |
| 10 | `database/sql.convertAssignRows` | 8.1MB | 5/292 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 120.74GB | 283/292 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/292 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/292 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/292 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 52.16GB | 283/292 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 50.22GB | 268/292 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/292 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/292 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 29.25GB | 281/292 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.87GB | 268/292 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
