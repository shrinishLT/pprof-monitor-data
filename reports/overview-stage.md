# Overview: stage
*Last updated: 2026-05-18 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T19:31 (152 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,258 | avg: 14,433 | max: 28,205 | trend: INCREASING (+21.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁
```

**Heap InUse** (current: 204.3MB | avg: 161.2MB | max: 732.9MB | trend: INCREASING (+1.10MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,258 | 26,211 | -11953 | 14,433 | 28,205 | INCREASING (+21.91/hr) |
| Heap InUse | 204.3MB | 536.1MB | -331.8MB | 161.2MB | 732.9MB | INCREASING (+1.10MB/hr) |
| Heap Sys | 1627.2MB | 1592.8MB | +34.4MB | 935.1MB | 1627.2MB | |
| Heap Objects | 1,060,303 | 1,570,459 | -510156 | 848,521 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 45 | 15,140 | 195.2MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 2.55MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 119.89GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 94.38GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 93.52GB |
| 4 | `internal/evaluation.mergeMetadata` | 91.14GB |
| 5 | `reflect.unsafe_NewArray` | 51.88GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.79GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 8 | `experiment/local.topologicalSort` | 46.64GB |
| 9 | `reflect.MakeSlice` | 28.74GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 150/152 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/152 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.65MB | 25/152 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/152 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.61MB | 146/152 | `████░░░░░░░░░░░ 31%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/152 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/152 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/152 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 149/152 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 141/152 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 60.55GB | 143/152 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.45GB | 128/152 | `███████░░░░░░░░ 46%` |
| 3 | `internal/evaluation.mergeMetadata` | 26.6GB | 139/152 | `██████░░░░░░░░░ 43%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 26.53GB | 145/152 | `██████░░░░░░░░░ 43%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 26.37GB | 144/152 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 26.17GB | 143/152 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 14.76GB | 141/152 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 13.51GB | 140/152 | `███░░░░░░░░░░░░ 22%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.44GB | 141/152 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.39GB | 128/152 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
