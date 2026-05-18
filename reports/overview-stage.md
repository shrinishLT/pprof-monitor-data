# Overview: stage
*Last updated: 2026-05-18 23:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T23:00 (159 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,421 | max: 28,205 | trend: INCREASING (+18.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 154.7MB | avg: 161.2MB | max: 732.9MB | trend: INCREASING (+0.97MB/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,271 | -196 | 14,421 | 28,205 | INCREASING (+18.23/hr) |
| Heap InUse | 154.7MB | 214.5MB | -59.8MB | 161.2MB | 732.9MB | INCREASING (+0.97MB/hr) |
| Heap Sys | 1633.4MB | 1633.0MB | +0.4MB | 965.8MB | 1633.4MB | |
| Heap Objects | 761,690 | 1,024,088 | -262398 | 842,348 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 52 | 15,007 | 190.9MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.06MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 126.08GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.69GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 96.85GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.35GB |
| 5 | `reflect.unsafe_NewArray` | 54.54GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.47GB |
| 7 | `experiment/local.topologicalSort` | 48.26GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 30.25GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 157/159 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/159 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/159 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/159 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.91MB | 153/159 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/159 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/159 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/159 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 156/159 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 148/159 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 63.48GB | 150/159 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.79GB | 146/159 | `███████░░░░░░░░ 46%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 29.75GB | 152/159 | `███████░░░░░░░░ 46%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 29.59GB | 151/159 | `██████░░░░░░░░░ 46%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 29.41GB | 135/159 | `██████░░░░░░░░░ 46%` |
| 6 | `reflect.unsafe_NewArray` | 27.45GB | 150/159 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 15.46GB | 148/159 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 15.13GB | 147/159 | `███░░░░░░░░░░░░ 23%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.11GB | 148/159 | `███░░░░░░░░░░░░ 23%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.81GB | 135/159 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
