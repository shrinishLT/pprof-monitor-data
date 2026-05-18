# Overview: stage
*Last updated: 2026-05-18 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T20:03 (153 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,093 | avg: 14,431 | max: 28,205 | trend: INCREASING (+21.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁
```

**Heap InUse** (current: 153.4MB | avg: 161.1MB | max: 732.9MB | trend: INCREASING (+1.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,093 | 14,258 | -165 | 14,431 | 28,205 | INCREASING (+21.31/hr) |
| Heap InUse | 153.4MB | 204.3MB | -50.9MB | 161.1MB | 732.9MB | INCREASING (+1.08MB/hr) |
| Heap Sys | 1628.7MB | 1627.2MB | +1.5MB | 939.7MB | 1628.7MB | |
| Heap Objects | 545,941 | 1,060,303 | -514362 | 846,543 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 46 | 15,117 | 194.3MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `reflect.unsafe_NewArray` | 2.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 120.84GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 94.93GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 94.09GB |
| 4 | `internal/evaluation.mergeMetadata` | 91.66GB |
| 5 | `reflect.unsafe_NewArray` | 52.31GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.05GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 8 | `experiment/local.topologicalSort` | 46.91GB |
| 9 | `reflect.MakeSlice` | 28.95GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 151/153 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/153 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.65MB | 25/153 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/153 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.66MB | 147/153 | `████░░░░░░░░░░░ 31%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/153 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/153 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/153 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 150/153 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 142/153 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 60.96GB | 144/153 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.59GB | 129/153 | `███████░░░░░░░░ 46%` |
| 3 | `internal/evaluation.mergeMetadata` | 27.06GB | 140/153 | `██████░░░░░░░░░ 44%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 26.99GB | 146/153 | `██████░░░░░░░░░ 44%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 26.84GB | 145/153 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 26.36GB | 144/153 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 14.86GB | 142/153 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 13.74GB | 141/153 | `███░░░░░░░░░░░░ 22%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.68GB | 142/153 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.45GB | 129/153 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
