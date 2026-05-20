# Overview: stage
*Last updated: 2026-05-20 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T22:31 (254 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,177 | avg: 14,313 | max: 28,205 | trend: INCREASING (+1.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁▃▁▂
```

**Heap InUse** (current: 196.1MB | avg: 167.1MB | max: 732.9MB | trend: stable (+0.42MB/hr))
```
▁▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂▁▂▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,177 | 14,083 | +94 | 14,313 | 28,205 | INCREASING (+1.35/hr) |
| Heap InUse | 196.1MB | 143.4MB | +52.7MB | 167.1MB | 732.9MB | stable (+0.42MB/hr) |
| Heap Sys | 1790.5MB | 1789.8MB | +0.7MB | 1262.4MB | 1790.5MB | |
| Heap Objects | 1,151,224 | 574,436 | +576788 | 865,974 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 46 | 14,140 | 179.6MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.01MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 211.25GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 129.99GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 129.2GB |
| 4 | `internal/evaluation.mergeMetadata` | 125.77GB |
| 5 | `reflect.unsafe_NewArray` | 91.11GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 65.57GB |
| 8 | `experiment/local.topologicalSort` | 64.32GB |
| 9 | `reflect.MakeSlice` | 50.87GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 252/254 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/254 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.24MB | 248/254 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/254 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/254 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/254 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 251/254 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/254 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 243/254 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/254 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 104.38GB | 245/254 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 61.7GB | 247/254 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 61.43GB | 246/254 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 61.05GB | 241/254 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 45.1GB | 245/254 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.25GB | 230/254 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.47GB | 243/254 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 31.1GB | 242/254 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 25.3GB | 243/254 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.26GB | 230/254 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
