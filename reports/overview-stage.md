# Overview: stage
*Last updated: 2026-05-21 02:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T02:30 (262 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,078 | avg: 14,306 | max: 28,205 | trend: INCREASING (+0.92/hr))
```
▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 193.8MB | avg: 167.3MB | max: 732.9MB | trend: stable (+0.39MB/hr))
```
▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,078 | 14,071 | +7 | 14,306 | 28,205 | INCREASING (+0.92/hr) |
| Heap InUse | 193.8MB | 165.1MB | +28.7MB | 167.3MB | 732.9MB | stable (+0.39MB/hr) |
| Heap Sys | 1789.6MB | 1790.9MB | -1.3MB | 1278.5MB | 1790.9MB | |
| Heap Objects | 1,028,185 | 883,839 | +144346 | 868,787 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 6 | 14,088 | 179.1MB | 203.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 218.36GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 132.62GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 131.89GB |
| 4 | `internal/evaluation.mergeMetadata` | 128.4GB |
| 5 | `reflect.unsafe_NewArray` | 94.24GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 67.0GB |
| 8 | `experiment/local.topologicalSort` | 65.67GB |
| 9 | `reflect.MakeSlice` | 52.65GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 260/262 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/262 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.36MB | 256/262 | `█████░░░░░░░░░░ 39%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/262 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/262 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/262 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 259/262 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/262 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 251/262 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/262 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 107.88GB | 253/262 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.86GB | 255/262 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.59GB | 254/262 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 63.15GB | 249/262 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 46.61GB | 253/262 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.41GB | 238/262 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 32.57GB | 251/262 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 32.17GB | 250/262 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 26.15GB | 251/262 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.77GB | 238/262 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
