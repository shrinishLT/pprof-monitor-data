# Overview: stage
*Last updated: 2026-05-19 17:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T17:02 (195 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,365 | max: 28,205 | trend: INCREASING (+7.10/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 153.1MB | avg: 164.0MB | max: 732.9MB | trend: INCREASING (+0.67MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,074 | -3 | 14,365 | 28,205 | INCREASING (+7.10/hr) |
| Heap InUse | 153.1MB | 195.3MB | -42.2MB | 164.0MB | 732.9MB | INCREASING (+0.67MB/hr) |
| Heap Sys | 1774.2MB | 1773.9MB | +0.3MB | 1105.3MB | 1774.2MB | |
| Heap Objects | 685,656 | 1,290,582 | -604926 | 854,524 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 35 | 14,119 | 177.5MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 158.23GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 108.86GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 108.07GB |
| 4 | `internal/evaluation.mergeMetadata` | 105.22GB |
| 5 | `reflect.unsafe_NewArray` | 68.36GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.32GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.95GB |
| 8 | `experiment/local.topologicalSort` | 53.84GB |
| 9 | `reflect.MakeSlice` | 38.02GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 193/195 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/195 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/195 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.07MB | 189/195 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/195 | `████░░░░░░░░░░░ 32%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/195 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/195 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.33MB | 18/195 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 192/195 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 184/195 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 78.78GB | 186/195 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 43.9GB | 188/195 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 43.71GB | 182/195 | `████████░░░░░░░ 55%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 43.68GB | 187/195 | `████████░░░░░░░ 55%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 34.94GB | 171/195 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 34.06GB | 186/195 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.41GB | 184/195 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 22.23GB | 183/195 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 19.13GB | 184/195 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.21GB | 171/195 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
