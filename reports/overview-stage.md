# Overview: stage
*Last updated: 2026-05-19 13:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T13:02 (187 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,373 | max: 28,205 | trend: INCREASING (+8.64/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 181.2MB | avg: 163.0MB | max: 732.9MB | trend: INCREASING (+0.70MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,201 | -133 | 14,373 | 28,205 | INCREASING (+8.64/hr) |
| Heap InUse | 181.2MB | 171.3MB | +9.9MB | 163.0MB | 732.9MB | INCREASING (+0.70MB/hr) |
| Heap Sys | 1772.0MB | 1771.4MB | +0.6MB | 1076.7MB | 1772.0MB | |
| Heap Objects | 1,117,255 | 651,187 | +466068 | 849,992 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 27 | 14,107 | 174.9MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewWriterSize` | 1.55MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 151.08GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 106.06GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 105.2GB |
| 4 | `internal/evaluation.mergeMetadata` | 102.44GB |
| 5 | `reflect.unsafe_NewArray` | 65.3GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.94GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.53GB |
| 8 | `experiment/local.topologicalSort` | 52.41GB |
| 9 | `reflect.MakeSlice` | 36.26GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.52GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 185/187 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/187 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/187 | `█████░░░░░░░░░░ 37%` |
| 4 | `runtime.mallocgc` | 12.85MB | 181/187 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/187 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/187 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/187 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/187 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 184/187 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 176/187 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 75.36GB | 178/187 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 41.06GB | 180/187 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 40.93GB | 174/187 | `████████░░░░░░░ 54%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 40.85GB | 179/187 | `████████░░░░░░░ 54%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.6GB | 163/187 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 32.58GB | 178/187 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.95GB | 176/187 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 20.81GB | 175/187 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.3GB | 176/187 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.62GB | 163/187 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
