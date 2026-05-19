# Overview: stage
*Last updated: 2026-05-19 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T08:01 (177 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,389 | max: 28,205 | trend: INCREASING (+11.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 208.1MB | avg: 162.7MB | max: 732.9MB | trend: INCREASING (+0.80MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,083 | -16 | 14,389 | 28,205 | INCREASING (+11.33/hr) |
| Heap InUse | 208.1MB | 152.4MB | +55.7MB | 162.7MB | 732.9MB | INCREASING (+0.80MB/hr) |
| Heap Sys | 1771.4MB | 1771.3MB | +0.1MB | 1037.5MB | 1771.4MB | |
| Heap Objects | 1,433,693 | 726,847 | +706846 | 845,808 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 17 | 14,117 | 177.8MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 142.04GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.1GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.24GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.54GB |
| 5 | `reflect.unsafe_NewArray` | 61.43GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.04GB |
| 8 | `experiment/local.topologicalSort` | 51.92GB |
| 9 | `reflect.MakeSlice` | 34.09GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 175/177 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/177 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/177 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/177 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.55MB | 171/177 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/177 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/177 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/177 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 174/177 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 166/177 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 71.1GB | 168/177 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 37.27GB | 170/177 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 37.21GB | 164/177 | `███████░░░░░░░░ 52%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 37.08GB | 169/177 | `███████░░░░░░░░ 52%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 31.84GB | 153/177 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 30.74GB | 168/177 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.01GB | 166/177 | `████░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 18.92GB | 165/177 | `███░░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 17.28GB | 166/177 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.86GB | 153/177 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
