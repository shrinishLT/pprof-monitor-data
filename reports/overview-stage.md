# Overview: stage
*Last updated: 2026-05-18 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T23:30 (160 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,418 | max: 28,205 | trend: INCREASING (+17.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 128.7MB | avg: 161.0MB | max: 732.9MB | trend: INCREASING (+0.94MB/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,075 | -5 | 14,418 | 28,205 | INCREASING (+17.73/hr) |
| Heap InUse | 128.7MB | 154.7MB | -26.0MB | 161.0MB | 732.9MB | INCREASING (+0.94MB/hr) |
| Heap Sys | 1634.4MB | 1633.4MB | +1.0MB | 969.9MB | 1634.4MB | |
| Heap Objects | 348,436 | 761,690 | -413254 | 839,261 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.06MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 126.96GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.73GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 96.89GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.38GB |
| 5 | `reflect.unsafe_NewArray` | 54.94GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.5GB |
| 7 | `experiment/local.topologicalSort` | 48.27GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 30.47GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 158/160 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/160 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/160 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/160 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.94MB | 154/160 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/160 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/160 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/160 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 157/160 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 149/160 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 63.9GB | 151/160 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.23GB | 147/160 | `███████░░░░░░░░ 47%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 30.2GB | 153/160 | `███████░░░░░░░░ 47%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 30.03GB | 152/160 | `███████░░░░░░░░ 46%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 29.54GB | 136/160 | `██████░░░░░░░░░ 46%` |
| 6 | `reflect.unsafe_NewArray` | 27.63GB | 151/160 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 15.56GB | 149/160 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 15.36GB | 148/160 | `███░░░░░░░░░░░░ 24%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.34GB | 149/160 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.86GB | 136/160 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
