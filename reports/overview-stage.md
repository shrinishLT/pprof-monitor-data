# Overview: stage
*Last updated: 2026-05-20 23:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T23:00 (255 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,312 | max: 28,205 | trend: INCREASING (+1.29/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁▃▁▂▁
```

**Heap InUse** (current: 149.2MB | avg: 167.0MB | max: 732.9MB | trend: stable (+0.41MB/hr))
```
▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂▁▂▁▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,177 | -102 | 14,312 | 28,205 | INCREASING (+1.29/hr) |
| Heap InUse | 149.2MB | 196.1MB | -46.9MB | 167.0MB | 732.9MB | stable (+0.41MB/hr) |
| Heap Sys | 1790.9MB | 1790.5MB | +0.4MB | 1264.5MB | 1790.9MB | |
| Heap Objects | 658,170 | 1,151,224 | -493054 | 865,159 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 47 | 14,139 | 179.0MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 212.09GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 130.06GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 129.28GB |
| 4 | `internal/evaluation.mergeMetadata` | 125.84GB |
| 5 | `reflect.unsafe_NewArray` | 91.47GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 65.61GB |
| 8 | `experiment/local.topologicalSort` | 64.37GB |
| 9 | `reflect.MakeSlice` | 51.07GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 253/255 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/255 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.26MB | 249/255 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/255 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/255 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/255 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 252/255 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/255 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 244/255 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/255 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 104.81GB | 246/255 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 61.98GB | 248/255 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 61.71GB | 247/255 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 61.32GB | 242/255 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 45.29GB | 246/255 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.4GB | 231/255 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.61GB | 244/255 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 31.24GB | 243/255 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 25.41GB | 244/255 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33GB | 231/255 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
