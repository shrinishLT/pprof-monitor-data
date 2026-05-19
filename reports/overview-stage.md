# Overview: stage
*Last updated: 2026-05-19 11:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T11:02 (183 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,379 | max: 28,205 | trend: INCREASING (+9.62/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 157.5MB | avg: 162.8MB | max: 732.9MB | trend: INCREASING (+0.73MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,070 | -5 | 14,379 | 28,205 | INCREASING (+9.62/hr) |
| Heap InUse | 157.5MB | 198.1MB | -40.6MB | 162.8MB | 732.9MB | INCREASING (+0.73MB/hr) |
| Heap Sys | 1771.5MB | 1771.5MB | +0.0MB | 1061.5MB | 1771.5MB | |
| Heap Objects | 827,196 | 1,276,983 | -449787 | 848,311 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 23 | 14,108 | 175.3MB | 293.9MB |

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
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 147.45GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.42GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.57GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.85GB |
| 5 | `reflect.unsafe_NewArray` | 63.77GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.21GB |
| 8 | `experiment/local.topologicalSort` | 52.09GB |
| 9 | `reflect.MakeSlice` | 35.38GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 181/183 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/183 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/183 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/183 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.73MB | 177/183 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/183 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/183 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/183 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 180/183 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 172/183 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 73.65GB | 174/183 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 39.59GB | 176/183 | `████████░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 39.49GB | 170/183 | `████████░░░░░░░ 53%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 39.39GB | 175/183 | `████████░░░░░░░ 53%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 32.92GB | 159/183 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 31.84GB | 174/183 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.2GB | 172/183 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 20.08GB | 171/183 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 17.89GB | 172/183 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.33GB | 159/183 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
