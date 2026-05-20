# Overview: stage
*Last updated: 2026-05-20 19:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T19:02 (247 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,355 | avg: 14,317 | max: 28,205 | trend: INCREASING (+1.65/hr))
```
▃▁▃▃▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅
```

**Heap InUse** (current: 163.8MB | avg: 167.1MB | max: 732.9MB | trend: stable (+0.45MB/hr))
```
▃▁▁▁▁▂▃▁▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,355 | 14,185 | +170 | 14,317 | 28,205 | INCREASING (+1.65/hr) |
| Heap InUse | 163.8MB | 161.9MB | +1.9MB | 167.1MB | 732.9MB | stable (+0.45MB/hr) |
| Heap Sys | 1787.0MB | 1786.5MB | +0.5MB | 1247.5MB | 1787.0MB | |
| Heap Objects | 635,258 | 761,489 | -126231 | 867,878 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 39 | 14,133 | 181.7MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `reflect.unsafe_NewArray` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 204.92GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 125.89GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 125.12GB |
| 4 | `internal/evaluation.mergeMetadata` | 121.8GB |
| 5 | `reflect.unsafe_NewArray` | 88.34GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 63.47GB |
| 8 | `experiment/local.topologicalSort` | 62.28GB |
| 9 | `reflect.MakeSlice` | 49.36GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 245/247 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/247 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.13MB | 241/247 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.03MB | 32/247 | `████░░░░░░░░░░░ 32%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/247 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/247 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 244/247 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/247 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 236/247 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/247 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 101.31GB | 238/247 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 59.76GB | 240/247 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 59.5GB | 239/247 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 59.16GB | 234/247 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 43.78GB | 238/247 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.17GB | 223/247 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.49GB | 236/247 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 30.13GB | 235/247 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.56GB | 236/247 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.79GB | 223/247 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
