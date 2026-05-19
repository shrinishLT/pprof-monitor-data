# Overview: stage
*Last updated: 2026-05-19 19:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T19:03 (199 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,320 | avg: 14,361 | max: 28,205 | trend: INCREASING (+6.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 175.5MB | avg: 164.5MB | max: 732.9MB | trend: INCREASING (+0.66MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,320 | 14,191 | +129 | 14,361 | 28,205 | INCREASING (+6.49/hr) |
| Heap InUse | 175.5MB | 213.0MB | -37.5MB | 164.5MB | 732.9MB | INCREASING (+0.66MB/hr) |
| Heap Sys | 1776.8MB | 1776.4MB | +0.4MB | 1118.8MB | 1776.8MB | |
| Heap Objects | 909,718 | 1,302,780 | -393062 | 858,231 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 39 | 14,127 | 178.5MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 161.79GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 109.56GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 108.8GB |
| 4 | `internal/evaluation.mergeMetadata` | 105.88GB |
| 5 | `reflect.unsafe_NewArray` | 69.92GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.4GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 55.3GB |
| 8 | `experiment/local.topologicalSort` | 54.16GB |
| 9 | `reflect.MakeSlice` | 38.86GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 197/199 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/199 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/199 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.17MB | 193/199 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/199 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/199 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.mergeMetadata` | 9.25MB | 6/199 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 196/199 | `███░░░░░░░░░░░░ 25%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 188/199 | `███░░░░░░░░░░░░ 24%` |
| 10 | `bufio.NewReaderSize` | 8.94MB | 19/199 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 80.5GB | 190/199 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 45.26GB | 192/199 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 45.04GB | 191/199 | `████████░░░░░░░ 55%` |
| 4 | `internal/evaluation.mergeMetadata` | 45.04GB | 186/199 | `████████░░░░░░░ 55%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 35.59GB | 175/199 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 34.81GB | 190/199 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.1GB | 188/199 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 22.91GB | 187/199 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 19.54GB | 188/199 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.49GB | 175/199 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
