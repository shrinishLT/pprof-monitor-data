# Overview: stage
*Last updated: 2026-05-19 09:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T09:00 (179 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,386 | max: 28,205 | trend: INCREASING (+10.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 156.9MB | avg: 162.5MB | max: 732.9MB | trend: INCREASING (+0.76MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,097 | -30 | 14,386 | 28,205 | INCREASING (+10.73/hr) |
| Heap InUse | 156.9MB | 148.3MB | +8.6MB | 162.5MB | 732.9MB | INCREASING (+0.76MB/hr) |
| Heap Sys | 1771.4MB | 1771.4MB | +0.0MB | 1045.7MB | 1771.4MB | |
| Heap Objects | 795,003 | 645,476 | +149527 | 844,405 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 19 | 14,113 | 175.2MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 143.75GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.21GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.36GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.65GB |
| 5 | `reflect.unsafe_NewArray` | 62.16GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.1GB |
| 8 | `experiment/local.topologicalSort` | 51.98GB |
| 9 | `reflect.MakeSlice` | 34.49GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 177/179 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/179 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/179 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/179 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.61MB | 173/179 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/179 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/179 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/179 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 176/179 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 168/179 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 71.94GB | 170/179 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 38.06GB | 172/179 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 37.99GB | 166/179 | `███████░░░░░░░░ 52%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 37.87GB | 171/179 | `███████░░░░░░░░ 52%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 32.21GB | 155/179 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 31.11GB | 170/179 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.41GB | 168/179 | `████░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 19.31GB | 167/179 | `████░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 17.49GB | 168/179 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.02GB | 155/179 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
