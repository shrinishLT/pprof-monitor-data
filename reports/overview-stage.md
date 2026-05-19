# Overview: stage
*Last updated: 2026-05-19 13:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T13:30 (188 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,228 | avg: 14,373 | max: 28,205 | trend: INCREASING (+8.45/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 187.7MB | avg: 163.2MB | max: 732.9MB | trend: INCREASING (+0.70MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,228 | 14,068 | +160 | 14,373 | 28,205 | INCREASING (+8.45/hr) |
| Heap InUse | 187.7MB | 181.2MB | +6.5MB | 163.2MB | 732.9MB | INCREASING (+0.70MB/hr) |
| Heap Sys | 1771.8MB | 1772.0MB | -0.2MB | 1080.4MB | 1772.0MB | |
| Heap Objects | 769,181 | 1,117,255 | -348074 | 849,562 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 28 | 14,111 | 175.4MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.03MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 151.93GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 106.21GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 105.36GB |
| 4 | `internal/evaluation.mergeMetadata` | 102.58GB |
| 5 | `reflect.unsafe_NewArray` | 65.68GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.94GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.62GB |
| 8 | `experiment/local.topologicalSort` | 52.49GB |
| 9 | `reflect.MakeSlice` | 36.48GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.52GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 186/188 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/188 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/188 | `█████░░░░░░░░░░ 37%` |
| 4 | `runtime.mallocgc` | 12.88MB | 182/188 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/188 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/188 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/188 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/188 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 185/188 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 177/188 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 75.79GB | 179/188 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 41.42GB | 181/188 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 41.28GB | 175/188 | `████████░░░░░░░ 54%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 41.21GB | 180/188 | `████████░░░░░░░ 54%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.76GB | 164/188 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 32.77GB | 179/188 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.13GB | 177/188 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 20.99GB | 176/188 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.41GB | 177/188 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.7GB | 164/188 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
