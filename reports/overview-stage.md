# Overview: stage
*Last updated: 2026-05-19 01:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T01:02 (163 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,117 | avg: 14,412 | max: 28,205 | trend: INCREASING (+16.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 197.5MB | avg: 161.2MB | max: 732.9MB | trend: INCREASING (+0.90MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,117 | 14,064 | +53 | 14,412 | 28,205 | INCREASING (+16.32/hr) |
| Heap InUse | 197.5MB | 135.9MB | +61.6MB | 161.2MB | 732.9MB | INCREASING (+0.90MB/hr) |
| Heap Sys | 1633.6MB | 1633.5MB | +0.1MB | 982.2MB | 1634.4MB | |
| Heap Objects | 1,295,904 | 527,223 | +768681 | 840,988 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 3 | 14,083 | 168.1MB | 197.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewWriterSize` | 2.06MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 129.75GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.85GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 97.02GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.53GB |
| 5 | `reflect.unsafe_NewArray` | 56.12GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.57GB |
| 7 | `experiment/local.topologicalSort` | 48.34GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 31.11GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 161/163 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/163 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/163 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/163 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.06MB | 157/163 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/163 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/163 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/163 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 160/163 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 152/163 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 65.17GB | 154/163 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.52GB | 150/163 | `███████░░░░░░░░ 48%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.5GB | 156/163 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 31.33GB | 155/163 | `███████░░░░░░░░ 48%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 29.92GB | 139/163 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 28.17GB | 154/163 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.02GB | 152/163 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 16.01GB | 151/163 | `███░░░░░░░░░░░░ 24%` |
| 9 | `reflect.MakeSlice` | 15.86GB | 152/163 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.03GB | 139/163 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
