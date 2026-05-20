# Overview: stage
*Last updated: 2026-05-20 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T23:30 (256 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,311 | max: 28,205 | trend: INCREASING (+1.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁
```

**Heap InUse** (current: 165.0MB | avg: 167.0MB | max: 732.9MB | trend: stable (+0.41MB/hr))
```
▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂▁▂▁▃▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,075 | -2 | 14,311 | 28,205 | INCREASING (+1.23/hr) |
| Heap InUse | 165.0MB | 149.2MB | +15.8MB | 167.0MB | 732.9MB | stable (+0.41MB/hr) |
| Heap Sys | 1790.9MB | 1790.9MB | +0.0MB | 1266.5MB | 1790.9MB | |
| Heap Objects | 891,658 | 658,170 | +233488 | 865,263 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 213.01GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 130.13GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 129.36GB |
| 4 | `internal/evaluation.mergeMetadata` | 125.9GB |
| 5 | `reflect.unsafe_NewArray` | 91.85GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 65.65GB |
| 8 | `experiment/local.topologicalSort` | 64.4GB |
| 9 | `reflect.MakeSlice` | 51.25GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 254/256 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/256 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.27MB | 250/256 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/256 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/256 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/256 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 253/256 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/256 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 245/256 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/256 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 105.25GB | 247/256 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 62.25GB | 249/256 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 61.98GB | 248/256 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 61.59GB | 243/256 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 45.48GB | 247/256 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.55GB | 232/256 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.75GB | 245/256 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 31.37GB | 244/256 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 25.51GB | 245/256 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.39GB | 232/256 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
