# Overview: stage
*Last updated: 2026-05-19 11:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T11:30 (184 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,378 | max: 28,205 | trend: INCREASING (+9.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 170.0MB | avg: 162.9MB | max: 732.9MB | trend: INCREASING (+0.72MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,065 | +2 | 14,378 | 28,205 | INCREASING (+9.35/hr) |
| Heap InUse | 170.0MB | 157.5MB | +12.5MB | 162.9MB | 732.9MB | INCREASING (+0.72MB/hr) |
| Heap Sys | 1771.5MB | 1771.5MB | +0.0MB | 1065.4MB | 1771.5MB | |
| Heap Objects | 978,004 | 827,196 | +150808 | 849,015 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 24 | 14,106 | 175.1MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 148.28GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.45GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.6GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.87GB |
| 5 | `reflect.unsafe_NewArray` | 64.13GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.22GB |
| 8 | `experiment/local.topologicalSort` | 52.1GB |
| 9 | `reflect.MakeSlice` | 35.6GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 182/184 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/184 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/184 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/184 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.76MB | 178/184 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/184 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/184 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/184 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 181/184 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 173/184 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 74.08GB | 175/184 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 39.96GB | 177/184 | `████████░░░░░░░ 53%` |
| 3 | `internal/evaluation.mergeMetadata` | 39.85GB | 171/184 | `████████░░░░░░░ 53%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 39.76GB | 176/184 | `████████░░░░░░░ 53%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.09GB | 160/184 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 32.03GB | 175/184 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.39GB | 173/184 | `████░░░░░░░░░░░ 27%` |
| 8 | `experiment/local.topologicalSort` | 20.26GB | 172/184 | `████░░░░░░░░░░░ 27%` |
| 9 | `reflect.MakeSlice` | 18.0GB | 173/184 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.4GB | 160/184 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
