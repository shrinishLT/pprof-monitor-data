# Overview: stage
*Last updated: 2026-05-19 02:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T02:01 (165 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,408 | max: 28,205 | trend: INCREASING (+15.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 150.7MB | avg: 161.0MB | max: 732.9MB | trend: INCREASING (+0.85MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,072 | -5 | 14,408 | 28,205 | INCREASING (+15.44/hr) |
| Heap InUse | 150.7MB | 150.2MB | +0.5MB | 161.0MB | 732.9MB | INCREASING (+0.85MB/hr) |
| Heap Sys | 1633.6MB | 1633.6MB | +0.0MB | 990.1MB | 1634.4MB | |
| Heap Objects | 711,700 | 712,802 | -1102 | 839,427 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 5 | 14,077 | 161.0MB | 197.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 7 | `reflect.mapassign_faststr0` | 4.0MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 131.43GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.87GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 97.05GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.56GB |
| 5 | `reflect.unsafe_NewArray` | 56.83GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.58GB |
| 7 | `experiment/local.topologicalSort` | 48.36GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 31.52GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 163/165 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/165 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/165 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/165 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.14MB | 159/165 | `████░░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/165 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/165 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/165 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 162/165 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 154/165 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 66.01GB | 156/165 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 32.35GB | 152/165 | `███████░░░░░░░░ 49%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 32.34GB | 158/165 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 32.16GB | 157/165 | `███████░░░░░░░░ 48%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.16GB | 141/165 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 28.54GB | 156/165 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.45GB | 154/165 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 16.44GB | 153/165 | `███░░░░░░░░░░░░ 24%` |
| 9 | `reflect.MakeSlice` | 16.06GB | 154/165 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.13GB | 141/165 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
