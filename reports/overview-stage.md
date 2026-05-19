# Overview: stage
*Last updated: 2026-05-19 15:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T15:00 (191 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,369 | max: 28,205 | trend: INCREASING (+7.82/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 175.3MB | avg: 163.4MB | max: 732.9MB | trend: INCREASING (+0.68MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,210 | -144 | 14,369 | 28,205 | INCREASING (+7.82/hr) |
| Heap InUse | 175.3MB | 182.8MB | -7.5MB | 163.4MB | 732.9MB | INCREASING (+0.68MB/hr) |
| Heap Sys | 1772.7MB | 1772.7MB | +0.0MB | 1091.3MB | 1772.7MB | |
| Heap Objects | 1,003,808 | 832,756 | +171052 | 849,997 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 31 | 14,113 | 175.5MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.03MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 154.49GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 107.63GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 106.81GB |
| 4 | `internal/evaluation.mergeMetadata` | 103.99GB |
| 5 | `reflect.unsafe_NewArray` | 66.79GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 62.22GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.33GB |
| 8 | `experiment/local.topologicalSort` | 53.22GB |
| 9 | `reflect.MakeSlice` | 37.13GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 189/191 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/191 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/191 | `█████░░░░░░░░░░ 37%` |
| 4 | `runtime.mallocgc` | 12.96MB | 185/191 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/191 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/191 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/191 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/191 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 188/191 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 180/191 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 77.07GB | 182/191 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 42.49GB | 184/191 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 42.33GB | 178/191 | `████████░░░░░░░ 54%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 42.28GB | 183/191 | `████████░░░░░░░ 54%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 34.27GB | 167/191 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 33.32GB | 182/191 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.68GB | 180/191 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 21.53GB | 179/191 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.72GB | 180/191 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.92GB | 167/191 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
