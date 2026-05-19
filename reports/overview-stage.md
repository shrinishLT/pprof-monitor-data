# Overview: stage
*Last updated: 2026-05-19 12:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T12:30 (186 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,201 | avg: 14,375 | max: 28,205 | trend: INCREASING (+8.89/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 171.3MB | avg: 163.0MB | max: 732.9MB | trend: INCREASING (+0.71MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,201 | 14,068 | +133 | 14,375 | 28,205 | INCREASING (+8.89/hr) |
| Heap InUse | 171.3MB | 169.5MB | +1.8MB | 163.0MB | 732.9MB | INCREASING (+0.71MB/hr) |
| Heap Sys | 1771.4MB | 1771.5MB | -0.1MB | 1073.0MB | 1771.5MB | |
| Heap Objects | 651,187 | 961,196 | -310009 | 848,555 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 26 | 14,108 | 174.7MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.05MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 150.15GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.56GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.74GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.99GB |
| 5 | `reflect.unsafe_NewArray` | 64.92GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.29GB |
| 8 | `experiment/local.topologicalSort` | 52.17GB |
| 9 | `reflect.MakeSlice` | 36.04GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 184/186 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/186 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/186 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/186 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.82MB | 180/186 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/186 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/186 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/186 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 183/186 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 175/186 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 74.93GB | 177/186 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 40.7GB | 179/186 | `████████░░░░░░░ 54%` |
| 3 | `internal/evaluation.mergeMetadata` | 40.57GB | 173/186 | `████████░░░░░░░ 54%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 40.49GB | 178/186 | `████████░░░░░░░ 54%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.43GB | 162/186 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 32.4GB | 177/186 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.76GB | 175/186 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 20.63GB | 174/186 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.2GB | 175/186 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.55GB | 162/186 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
