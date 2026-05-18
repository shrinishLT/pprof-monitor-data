# Overview: stage
*Last updated: 2026-05-19 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T05:00 (171 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,396 | max: 28,205 | trend: INCREASING (+13.07/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 158.5MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+0.76MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,070 | -3 | 14,396 | 28,205 | INCREASING (+13.07/hr) |
| Heap InUse | 158.5MB | 209.1MB | -50.6MB | 160.9MB | 732.9MB | INCREASING (+0.76MB/hr) |
| Heap Sys | 1634.3MB | 1634.2MB | +0.1MB | 1012.7MB | 1635.0MB | |
| Heap Objects | 783,327 | 1,442,296 | -658969 | 836,594 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 11 | 14,074 | 159.6MB | 209.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.05MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 136.73GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 101.36GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 100.51GB |
| 4 | `internal/evaluation.mergeMetadata` | 97.93GB |
| 5 | `reflect.unsafe_NewArray` | 59.1GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.35GB |
| 7 | `experiment/local.topologicalSort` | 50.08GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 32.8GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 169/171 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/171 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/171 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/171 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.35MB | 165/171 | `█████░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/171 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/171 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/171 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 168/171 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 160/171 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 68.55GB | 162/171 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 34.84GB | 164/171 | `███████░░░░░░░░ 50%` |
| 3 | `internal/evaluation.mergeMetadata` | 34.82GB | 158/171 | `███████░░░░░░░░ 50%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 34.66GB | 163/171 | `███████░░░░░░░░ 50%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.85GB | 147/171 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 29.64GB | 162/171 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.75GB | 160/171 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 17.7GB | 159/171 | `███░░░░░░░░░░░░ 25%` |
| 9 | `reflect.MakeSlice` | 16.67GB | 160/171 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.43GB | 147/171 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
