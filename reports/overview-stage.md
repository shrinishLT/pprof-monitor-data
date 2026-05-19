# Overview: stage
*Last updated: 2026-05-19 06:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T06:30 (174 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,367 | avg: 14,394 | max: 28,205 | trend: INCREASING (+12.28/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 269.0MB | avg: 162.4MB | max: 732.9MB | trend: INCREASING (+0.82MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,367 | 14,421 | -54 | 14,394 | 28,205 | INCREASING (+12.28/hr) |
| Heap InUse | 269.0MB | 293.9MB | -24.9MB | 162.4MB | 732.9MB | INCREASING (+0.82MB/hr) |
| Heap Sys | 1771.2MB | 1750.0MB | +21.2MB | 1024.8MB | 1771.2MB | |
| Heap Objects | 1,305,855 | 1,234,562 | +71293 | 842,134 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 14 | 14,119 | 177.6MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.04MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 139.43GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 104.47GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 103.62GB |
| 4 | `internal/evaluation.mergeMetadata` | 100.97GB |
| 5 | `reflect.unsafe_NewArray` | 60.3GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 59.98GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 52.75GB |
| 8 | `experiment/local.topologicalSort` | 51.62GB |
| 9 | `reflect.MakeSlice` | 33.49GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.11GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 172/174 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/174 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/174 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/174 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.45MB | 168/174 | `█████░░░░░░░░░░ 33%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/174 | `████░░░░░░░░░░░ 28%` |
| 7 | `bufio.NewReaderSize` | 10.21MB | 16/174 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/174 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 171/174 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 163/174 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 69.82GB | 165/174 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 36.06GB | 167/174 | `███████░░░░░░░░ 51%` |
| 3 | `internal/evaluation.mergeMetadata` | 36.01GB | 161/174 | `███████░░░░░░░░ 51%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 35.87GB | 166/174 | `███████░░░░░░░░ 51%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 31.27GB | 150/174 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 30.19GB | 165/174 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.38GB | 163/174 | `███░░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 18.31GB | 162/174 | `███░░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 16.98GB | 163/174 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.61GB | 150/174 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
