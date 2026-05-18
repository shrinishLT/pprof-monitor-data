# Overview: stage
*Last updated: 2026-05-19 04:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T04:30 (170 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,398 | max: 28,205 | trend: INCREASING (+13.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 209.1MB | avg: 161.0MB | max: 732.9MB | trend: INCREASING (+0.78MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,073 | -3 | 14,398 | 28,205 | INCREASING (+13.44/hr) |
| Heap InUse | 209.1MB | 130.0MB | +79.1MB | 161.0MB | 732.9MB | INCREASING (+0.78MB/hr) |
| Heap Sys | 1634.2MB | 1635.0MB | -0.8MB | 1009.0MB | 1635.0MB | |
| Heap Objects | 1,442,296 | 306,619 | +1135677 | 836,907 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 10 | 14,075 | 159.7MB | 209.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.05MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 135.84GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 101.36GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 100.51GB |
| 4 | `internal/evaluation.mergeMetadata` | 97.93GB |
| 5 | `reflect.unsafe_NewArray` | 58.74GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.35GB |
| 7 | `experiment/local.topologicalSort` | 50.08GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 32.59GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 168/170 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/170 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/170 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/170 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.31MB | 164/170 | `█████░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/170 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/170 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/170 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 167/170 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 159/170 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 68.13GB | 161/170 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 34.43GB | 163/170 | `███████░░░░░░░░ 50%` |
| 3 | `internal/evaluation.mergeMetadata` | 34.42GB | 157/170 | `███████░░░░░░░░ 50%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 34.25GB | 162/170 | `███████░░░░░░░░ 50%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.74GB | 146/170 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 29.45GB | 161/170 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.54GB | 159/170 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 17.49GB | 158/170 | `███░░░░░░░░░░░░ 25%` |
| 9 | `reflect.MakeSlice` | 16.57GB | 159/170 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.38GB | 146/170 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
