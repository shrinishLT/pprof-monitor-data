# Overview: stage
*Last updated: 2026-05-19 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T05:30 (172 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,394 | max: 28,205 | trend: INCREASING (+12.71/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 168.4MB | avg: 161.0MB | max: 732.9MB | trend: INCREASING (+0.75MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,394 | 28,205 | INCREASING (+12.71/hr) |
| Heap InUse | 168.4MB | 158.5MB | +9.9MB | 161.0MB | 732.9MB | INCREASING (+0.75MB/hr) |
| Heap Sys | 1634.3MB | 1634.3MB | +0.0MB | 1016.3MB | 1635.0MB | |
| Heap Objects | 933,299 | 783,327 | +149972 | 837,156 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 12 | 14,074 | 160.3MB | 209.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.55MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 137.6GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 101.38GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 100.53GB |
| 4 | `internal/evaluation.mergeMetadata` | 97.96GB |
| 5 | `reflect.unsafe_NewArray` | 59.5GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.36GB |
| 7 | `experiment/local.topologicalSort` | 50.1GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 33.01GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 170/172 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/172 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/172 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/172 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.38MB | 166/172 | `█████░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/172 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/172 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/172 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 169/172 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 161/172 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 68.97GB | 163/172 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 35.24GB | 165/172 | `███████░░░░░░░░ 51%` |
| 3 | `internal/evaluation.mergeMetadata` | 35.21GB | 159/172 | `███████░░░░░░░░ 51%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 35.06GB | 164/172 | `███████░░░░░░░░ 50%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.96GB | 148/172 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 29.82GB | 163/172 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.96GB | 161/172 | `███░░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 17.9GB | 160/172 | `███░░░░░░░░░░░░ 25%` |
| 9 | `reflect.MakeSlice` | 16.77GB | 161/172 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.48GB | 148/172 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
