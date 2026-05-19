# Overview: stage
*Last updated: 2026-05-19 12:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T12:02 (185 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,376 | max: 28,205 | trend: INCREASING (+9.09/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 169.5MB | avg: 162.9MB | max: 732.9MB | trend: INCREASING (+0.71MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,067 | +1 | 14,376 | 28,205 | INCREASING (+9.09/hr) |
| Heap InUse | 169.5MB | 170.0MB | -0.5MB | 162.9MB | 732.9MB | INCREASING (+0.71MB/hr) |
| Heap Sys | 1771.5MB | 1771.5MB | +0.0MB | 1069.2MB | 1771.5MB | |
| Heap Objects | 961,196 | 978,004 | -16808 | 849,622 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 25 | 14,105 | 174.8MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 149.23GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.45GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.61GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.87GB |
| 5 | `reflect.unsafe_NewArray` | 64.54GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.22GB |
| 8 | `experiment/local.topologicalSort` | 52.1GB |
| 9 | `reflect.MakeSlice` | 35.81GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 183/185 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/185 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/185 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/185 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.79MB | 179/185 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/185 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/185 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/185 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 182/185 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 174/185 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 74.5GB | 176/185 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 40.33GB | 178/185 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 40.21GB | 172/185 | `████████░░░░░░░ 53%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 40.13GB | 177/185 | `████████░░░░░░░ 53%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.26GB | 161/185 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 32.21GB | 176/185 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.58GB | 174/185 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 20.45GB | 173/185 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.1GB | 174/185 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.48GB | 161/185 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
