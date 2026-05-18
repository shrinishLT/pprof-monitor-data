# Overview: stage
*Last updated: 2026-05-18 20:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T20:30 (154 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,218 | avg: 14,430 | max: 28,205 | trend: INCREASING (+20.79/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁
```

**Heap InUse** (current: 136.2MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+1.04MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,218 | 14,093 | +125 | 14,430 | 28,205 | INCREASING (+20.79/hr) |
| Heap InUse | 136.2MB | 153.4MB | -17.2MB | 160.9MB | 732.9MB | INCREASING (+1.04MB/hr) |
| Heap Sys | 1629.6MB | 1628.7MB | +0.9MB | 944.1MB | 1629.6MB | |
| Heap Objects | 396,433 | 545,941 | -149508 | 843,620 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 47 | 15,098 | 193.1MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bufio.NewWriterSize` | 2.55MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 121.66GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 95.74GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 94.87GB |
| 4 | `internal/evaluation.mergeMetadata` | 92.41GB |
| 5 | `reflect.unsafe_NewArray` | 52.63GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.44GB |
| 7 | `experiment/local.topologicalSort` | 47.28GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.0GB |
| 9 | `reflect.MakeSlice` | 29.16GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 152/154 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/154 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.65MB | 25/154 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/154 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.7MB | 148/154 | `████░░░░░░░░░░░ 31%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/154 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/154 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/154 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 151/154 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 143/154 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 61.38GB | 145/154 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.73GB | 130/154 | `███████░░░░░░░░ 46%` |
| 3 | `internal/evaluation.mergeMetadata` | 27.53GB | 141/154 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.46GB | 147/154 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 27.31GB | 146/154 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 26.54GB | 145/154 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 14.96GB | 143/154 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 13.98GB | 142/154 | `███░░░░░░░░░░░░ 22%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.92GB | 143/154 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.51GB | 130/154 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
