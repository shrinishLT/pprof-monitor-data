# Overview: stage
*Last updated: 2026-05-19 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T18:02 (197 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,234 | avg: 14,362 | max: 28,205 | trend: INCREASING (+6.75/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 188.2MB | avg: 164.2MB | max: 732.9MB | trend: INCREASING (+0.66MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,234 | 14,074 | +160 | 14,362 | 28,205 | INCREASING (+6.75/hr) |
| Heap InUse | 188.2MB | 173.7MB | +14.5MB | 164.2MB | 732.9MB | INCREASING (+0.66MB/hr) |
| Heap Sys | 1774.1MB | 1774.2MB | -0.1MB | 1112.1MB | 1774.2MB | |
| Heap Objects | 943,446 | 999,863 | -56417 | 855,713 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 37 | 14,121 | 177.7MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 160.04GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 108.95GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 108.17GB |
| 4 | `internal/evaluation.mergeMetadata` | 105.3GB |
| 5 | `reflect.unsafe_NewArray` | 69.14GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.39GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.99GB |
| 8 | `experiment/local.topologicalSort` | 53.88GB |
| 9 | `reflect.MakeSlice` | 38.45GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 195/197 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/197 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/197 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.12MB | 191/197 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/197 | `████░░░░░░░░░░░ 32%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/197 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/197 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.33MB | 18/197 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 194/197 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 186/197 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 79.64GB | 188/197 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 44.59GB | 190/197 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 44.38GB | 184/197 | `████████░░░░░░░ 55%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 44.36GB | 189/197 | `████████░░░░░░░ 55%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 35.27GB | 173/197 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 34.43GB | 188/197 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.76GB | 186/197 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 22.57GB | 185/197 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 19.34GB | 186/197 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.35GB | 173/197 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
