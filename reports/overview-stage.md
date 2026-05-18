# Overview: stage
*Last updated: 2026-05-19 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T01:30 (164 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,072 | avg: 14,410 | max: 28,205 | trend: INCREASING (+15.87/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 150.2MB | avg: 161.1MB | max: 732.9MB | trend: INCREASING (+0.87MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,072 | 14,117 | -45 | 14,410 | 28,205 | INCREASING (+15.87/hr) |
| Heap InUse | 150.2MB | 197.5MB | -47.3MB | 161.1MB | 732.9MB | INCREASING (+0.87MB/hr) |
| Heap Sys | 1633.6MB | 1633.6MB | +0.0MB | 986.1MB | 1634.4MB | |
| Heap Objects | 712,802 | 1,295,904 | -583102 | 840,206 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 4 | 14,080 | 163.6MB | 197.5MB |

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
| 1 | `segmentio/kafka-go.makePartitions` | 130.5GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.87GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 97.05GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.56GB |
| 5 | `reflect.unsafe_NewArray` | 56.45GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.58GB |
| 7 | `experiment/local.topologicalSort` | 48.36GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 31.29GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 162/164 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/164 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/164 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/164 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.1MB | 158/164 | `████░░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/164 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/164 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/164 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 161/164 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 153/164 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 65.59GB | 155/164 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.93GB | 151/164 | `███████░░░░░░░░ 48%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 31.92GB | 157/164 | `███████░░░░░░░░ 48%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 31.75GB | 156/164 | `███████░░░░░░░░ 48%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.04GB | 140/164 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 28.36GB | 155/164 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.24GB | 153/164 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 16.23GB | 152/164 | `███░░░░░░░░░░░░ 24%` |
| 9 | `reflect.MakeSlice` | 15.96GB | 153/164 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.08GB | 140/164 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
