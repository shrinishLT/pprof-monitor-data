# Overview: stage
*Last updated: 2026-05-19 00:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T00:33 (162 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,414 | max: 28,205 | trend: INCREASING (+16.76/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 135.9MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+0.90MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,067 | -3 | 14,414 | 28,205 | INCREASING (+16.76/hr) |
| Heap InUse | 135.9MB | 170.9MB | -35.0MB | 160.9MB | 732.9MB | INCREASING (+0.90MB/hr) |
| Heap Sys | 1633.5MB | 1633.5MB | +0.0MB | 978.1MB | 1634.4MB | |
| Heap Objects | 527,223 | 976,102 | -448879 | 838,180 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 2 | 14,066 | 153.4MB | 170.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.06MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 128.87GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.79GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 96.94GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.44GB |
| 5 | `reflect.unsafe_NewArray` | 55.74GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.53GB |
| 7 | `experiment/local.topologicalSort` | 48.3GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 30.9GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 160/162 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/162 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/162 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/162 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.02MB | 156/162 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/162 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/162 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/162 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 159/162 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 151/162 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 64.75GB | 153/162 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.09GB | 149/162 | `███████░░░░░░░░ 48%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.07GB | 155/162 | `███████░░░░░░░░ 47%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 30.9GB | 154/162 | `███████░░░░░░░░ 47%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 29.79GB | 138/162 | `██████░░░░░░░░░ 46%` |
| 6 | `reflect.unsafe_NewArray` | 27.99GB | 153/162 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 15.8GB | 150/162 | `███░░░░░░░░░░░░ 24%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.8GB | 151/162 | `███░░░░░░░░░░░░ 24%` |
| 9 | `reflect.MakeSlice` | 15.76GB | 151/162 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.97GB | 138/162 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
