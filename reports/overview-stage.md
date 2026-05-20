# Overview: stage
*Last updated: 2026-05-20 20:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T20:30 (250 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,317 | avg: 14,316 | max: 28,205 | trend: INCREASING (+1.55/hr))
```
▃▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄
```

**Heap InUse** (current: 180.5MB | avg: 167.2MB | max: 732.9MB | trend: stable (+0.44MB/hr))
```
▁▁▂▃▁▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,317 | 14,263 | +54 | 14,316 | 28,205 | INCREASING (+1.55/hr) |
| Heap InUse | 180.5MB | 152.8MB | +27.7MB | 167.2MB | 732.9MB | stable (+0.44MB/hr) |
| Heap Sys | 1788.0MB | 1787.8MB | +0.2MB | 1254.0MB | 1788.0MB | |
| Heap Objects | 759,383 | 559,457 | +199926 | 867,789 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 42 | 14,141 | 181.4MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `reflect.unsafe_New` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 207.55GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 127.95GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 127.17GB |
| 4 | `internal/evaluation.mergeMetadata` | 123.8GB |
| 5 | `reflect.unsafe_NewArray` | 89.51GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 64.52GB |
| 8 | `experiment/local.topologicalSort` | 63.33GB |
| 9 | `reflect.MakeSlice` | 49.99GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 248/250 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/250 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.18MB | 244/250 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 11.71MB | 33/250 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/250 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/250 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 247/250 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/250 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 239/250 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/250 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.62GB | 241/250 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 60.59GB | 243/250 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 60.33GB | 242/250 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 59.97GB | 237/250 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 44.35GB | 241/250 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.64GB | 226/250 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.91GB | 239/250 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 30.55GB | 238/250 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.88GB | 239/250 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.0GB | 226/250 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
