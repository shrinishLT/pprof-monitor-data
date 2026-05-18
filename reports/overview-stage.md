# Overview: stage
*Last updated: 2026-05-19 00:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T00:00 (161 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,416 | max: 28,205 | trend: INCREASING (+17.24/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 170.9MB | avg: 161.1MB | max: 732.9MB | trend: INCREASING (+0.92MB/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,070 | -3 | 14,416 | 28,205 | INCREASING (+17.24/hr) |
| Heap InUse | 170.9MB | 128.7MB | +42.2MB | 161.1MB | 732.9MB | INCREASING (+0.92MB/hr) |
| Heap Sys | 1633.5MB | 1634.4MB | -0.9MB | 974.1MB | 1634.4MB | |
| Heap Objects | 976,102 | 348,436 | +627666 | 840,111 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 1 | 14,067 | 170.9MB | 170.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.06MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 127.87GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.76GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 96.92GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.41GB |
| 5 | `reflect.unsafe_NewArray` | 55.32GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.52GB |
| 7 | `experiment/local.topologicalSort` | 48.29GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 30.66GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 159/161 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/161 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/161 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/161 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.98MB | 155/161 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/161 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/161 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/161 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 158/161 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 150/161 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 64.32GB | 152/161 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.67GB | 148/161 | `███████░░░░░░░░ 47%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 30.63GB | 154/161 | `███████░░░░░░░░ 47%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 30.47GB | 153/161 | `███████░░░░░░░░ 47%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 29.67GB | 137/161 | `██████░░░░░░░░░ 46%` |
| 6 | `reflect.unsafe_NewArray` | 27.81GB | 152/161 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 15.66GB | 150/161 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 15.58GB | 149/161 | `███░░░░░░░░░░░░ 24%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.57GB | 150/161 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.92GB | 137/161 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
