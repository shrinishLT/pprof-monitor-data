# Overview: stage
*Last updated: 2026-05-19 15:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T15:31 (192 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,392 | avg: 14,369 | max: 28,205 | trend: INCREASING (+7.71/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 227.9MB | avg: 163.7MB | max: 732.9MB | trend: INCREASING (+0.69MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,392 | 14,066 | +326 | 14,369 | 28,205 | INCREASING (+7.71/hr) |
| Heap InUse | 227.9MB | 175.3MB | +52.6MB | 163.7MB | 732.9MB | INCREASING (+0.69MB/hr) |
| Heap Sys | 1773.2MB | 1772.7MB | +0.5MB | 1094.8MB | 1773.2MB | |
| Heap Objects | 1,236,106 | 1,003,808 | +232298 | 852,008 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 32 | 14,122 | 177.2MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bufio.NewWriterSize` | 4.04MB |
| 6 | `bufio.NewReaderSize` | 3.03MB |
| 7 | `bytes.growSlice` | 3.01MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 155.47GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 108.3GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 107.52GB |
| 4 | `internal/evaluation.mergeMetadata` | 104.68GB |
| 5 | `reflect.unsafe_NewArray` | 67.2GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 62.22GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.7GB |
| 8 | `experiment/local.topologicalSort` | 53.55GB |
| 9 | `reflect.MakeSlice` | 37.37GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 190/192 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/192 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/192 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 12.99MB | 186/192 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/192 | `████░░░░░░░░░░░ 32%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/192 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/192 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.33MB | 18/192 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 189/192 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 181/192 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 77.5GB | 183/192 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 42.85GB | 185/192 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 42.68GB | 179/192 | `████████░░░░░░░ 55%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 42.63GB | 184/192 | `████████░░░░░░░ 55%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 34.44GB | 168/192 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 33.51GB | 183/192 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.87GB | 181/192 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 21.71GB | 180/192 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 18.82GB | 181/192 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.99GB | 168/192 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
