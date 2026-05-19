# Overview: stage
*Last updated: 2026-05-19 14:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T14:01 (189 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,110 | avg: 14,371 | max: 28,205 | trend: INCREASING (+8.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.7MB | avg: 163.2MB | max: 732.9MB | trend: INCREASING (+0.69MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,110 | 14,228 | -118 | 14,371 | 28,205 | INCREASING (+8.23/hr) |
| Heap InUse | 172.7MB | 187.7MB | -15.0MB | 163.2MB | 732.9MB | INCREASING (+0.69MB/hr) |
| Heap Sys | 1772.3MB | 1771.8MB | +0.5MB | 1084.1MB | 1772.3MB | |
| Heap Objects | 795,278 | 769,181 | +26097 | 849,275 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 29 | 14,111 | 175.3MB | 293.9MB |

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
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.growslice` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 152.84GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 106.7GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 105.85GB |
| 4 | `internal/evaluation.mergeMetadata` | 103.07GB |
| 5 | `reflect.unsafe_NewArray` | 66.06GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 61.55GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.88GB |
| 8 | `experiment/local.topologicalSort` | 52.76GB |
| 9 | `reflect.MakeSlice` | 36.72GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.79GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 187/189 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/189 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/189 | `█████░░░░░░░░░░ 37%` |
| 4 | `runtime.mallocgc` | 12.91MB | 183/189 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/189 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/189 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/189 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/189 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 186/189 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 178/189 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 76.21GB | 180/189 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 41.78GB | 182/189 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 41.63GB | 176/189 | `████████░░░░░░░ 54%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 41.57GB | 181/189 | `████████░░░░░░░ 54%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.93GB | 165/189 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 32.95GB | 180/189 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.32GB | 178/189 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 21.17GB | 177/189 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.51GB | 178/189 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.77GB | 165/189 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
