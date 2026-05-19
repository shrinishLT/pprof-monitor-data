# Overview: stage
*Last updated: 2026-05-19 10:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T10:02 (181 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,125 | avg: 14,383 | max: 28,205 | trend: INCREASING (+10.17/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 159.5MB | avg: 162.7MB | max: 732.9MB | trend: INCREASING (+0.75MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,125 | 14,074 | +51 | 14,383 | 28,205 | INCREASING (+10.17/hr) |
| Heap InUse | 159.5MB | 188.4MB | -28.9MB | 162.7MB | 732.9MB | INCREASING (+0.75MB/hr) |
| Heap Sys | 1771.5MB | 1771.5MB | +0.0MB | 1053.7MB | 1771.5MB | |
| Heap Objects | 803,647 | 1,184,451 | -380804 | 846,059 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 21 | 14,112 | 175.0MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 145.63GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.3GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.46GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.76GB |
| 5 | `reflect.unsafe_NewArray` | 62.96GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.15GB |
| 8 | `experiment/local.topologicalSort` | 52.03GB |
| 9 | `reflect.MakeSlice` | 34.94GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 179/181 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/181 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/181 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/181 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.67MB | 175/181 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/181 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/181 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/181 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 178/181 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 170/181 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 72.8GB | 172/181 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 38.84GB | 174/181 | `████████░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 38.75GB | 168/181 | `███████░░░░░░░░ 53%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 38.64GB | 173/181 | `███████░░░░░░░░ 53%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 32.57GB | 157/181 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 31.47GB | 172/181 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.81GB | 170/181 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 19.7GB | 169/181 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 17.69GB | 170/181 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.18GB | 157/181 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
