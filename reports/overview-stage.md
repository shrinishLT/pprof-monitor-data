# Overview: stage
*Last updated: 2026-05-19 03:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T03:01 (167 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,090 | avg: 14,404 | max: 28,205 | trend: INCREASING (+14.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 169.6MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+0.81MB/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,090 | 14,067 | +23 | 14,404 | 28,205 | INCREASING (+14.61/hr) |
| Heap InUse | 169.6MB | 126.6MB | +43.0MB | 160.9MB | 732.9MB | INCREASING (+0.81MB/hr) |
| Heap Sys | 1633.8MB | 1633.8MB | +0.0MB | 997.8MB | 1634.4MB | |
| Heap Objects | 882,392 | 355,170 | +527222 | 836,785 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 7 | 14,078 | 157.3MB | 197.5MB |

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
| 1 | `segmentio/kafka-go.makePartitions` | 133.21GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 100.35GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 99.49GB |
| 4 | `internal/evaluation.mergeMetadata` | 96.93GB |
| 5 | `reflect.unsafe_NewArray` | 57.63GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 50.82GB |
| 7 | `experiment/local.topologicalSort` | 49.58GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 31.96GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 165/167 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/167 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/167 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/167 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.21MB | 161/167 | `█████░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/167 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/167 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/167 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 164/167 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 156/167 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 66.86GB | 158/167 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 33.19GB | 160/167 | `███████░░░░░░░░ 49%` |
| 3 | `internal/evaluation.mergeMetadata` | 33.19GB | 154/167 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.01GB | 159/167 | `███████░░░░░░░░ 49%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.39GB | 143/167 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 28.91GB | 158/167 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.89GB | 156/167 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 16.86GB | 155/167 | `███░░░░░░░░░░░░ 25%` |
| 9 | `reflect.MakeSlice` | 16.27GB | 156/167 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.23GB | 143/167 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
