# Overview: stage
*Last updated: 2026-05-19 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T10:30 (182 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,381 | max: 28,205 | trend: INCREASING (+9.89/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 198.1MB | avg: 162.9MB | max: 732.9MB | trend: INCREASING (+0.75MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,125 | -55 | 14,381 | 28,205 | INCREASING (+9.89/hr) |
| Heap InUse | 198.1MB | 159.5MB | +38.6MB | 162.9MB | 732.9MB | INCREASING (+0.75MB/hr) |
| Heap Sys | 1771.5MB | 1771.5MB | +0.0MB | 1057.6MB | 1771.5MB | |
| Heap Objects | 1,276,983 | 803,647 | +473336 | 848,427 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 22 | 14,110 | 176.1MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.unsafe_NewArray` | 3.02MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 146.48GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.32GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.48GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.77GB |
| 5 | `reflect.unsafe_NewArray` | 63.35GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.16GB |
| 8 | `experiment/local.topologicalSort` | 52.04GB |
| 9 | `reflect.MakeSlice` | 35.15GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 180/182 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/182 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/182 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/182 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.7MB | 176/182 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/182 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/182 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/182 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 179/182 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 171/182 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 73.22GB | 173/182 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 39.22GB | 175/182 | `████████░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 39.12GB | 169/182 | `████████░░░░░░░ 53%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 39.02GB | 174/182 | `███████░░░░░░░░ 53%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 32.74GB | 158/182 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 31.66GB | 173/182 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.0GB | 171/182 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 19.89GB | 170/182 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 17.79GB | 171/182 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.25GB | 158/182 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
