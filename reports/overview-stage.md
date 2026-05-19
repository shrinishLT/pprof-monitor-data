# Overview: stage
*Last updated: 2026-05-19 14:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T14:30 (190 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,210 | avg: 14,370 | max: 28,205 | trend: INCREASING (+8.05/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 182.8MB | avg: 163.3MB | max: 732.9MB | trend: INCREASING (+0.69MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,210 | 14,110 | +100 | 14,370 | 28,205 | INCREASING (+8.05/hr) |
| Heap InUse | 182.8MB | 172.7MB | +10.1MB | 163.3MB | 732.9MB | INCREASING (+0.69MB/hr) |
| Heap Sys | 1772.7MB | 1772.3MB | +0.4MB | 1087.7MB | 1772.7MB | |
| Heap Objects | 832,756 | 795,278 | +37478 | 849,188 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 30 | 14,114 | 175.6MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 153.7GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 107.54GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 106.72GB |
| 4 | `internal/evaluation.mergeMetadata` | 103.91GB |
| 5 | `reflect.unsafe_NewArray` | 66.44GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 62.21GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.29GB |
| 8 | `experiment/local.topologicalSort` | 53.18GB |
| 9 | `reflect.MakeSlice` | 36.92GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 188/190 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/190 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/190 | `█████░░░░░░░░░░ 37%` |
| 4 | `runtime.mallocgc` | 12.93MB | 184/190 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/190 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/190 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/190 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/190 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 187/190 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 179/190 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 76.64GB | 181/190 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 42.14GB | 183/190 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 41.98GB | 177/190 | `████████░░░░░░░ 54%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 41.93GB | 182/190 | `████████░░░░░░░ 54%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 34.1GB | 166/190 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 33.14GB | 181/190 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.5GB | 179/190 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 21.35GB | 178/190 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.61GB | 179/190 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.84GB | 166/190 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
