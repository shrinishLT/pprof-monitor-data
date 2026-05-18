# Overview: stage
*Last updated: 2026-05-18 19:04 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T19:04 (151 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 26,211 | avg: 14,434 | max: 28,205 | trend: INCREASING (+22.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇
```

**Heap InUse** (current: 536.1MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+1.10MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅
```

## Current Status

Goroutines: `██████████████████░░ 92%`
Heap InUse: `██████░░░░░░░░░░░░░░ 33%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 26,211 | 28,205 | -1994 | 14,434 | 28,205 | INCREASING (+22.44/hr) |
| Heap InUse | 536.1MB | 732.9MB | -196.8MB | 160.9MB | 732.9MB | INCREASING (+1.10MB/hr) |
| Heap Sys | 1592.8MB | 1592.0MB | +0.8MB | 930.5MB | 1592.8MB | |
| Heap Objects | 1,570,459 | 2,432,873 | -862414 | 847,118 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 44 | 15,160 | 195.0MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 74.87MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewWriterSize` | 34.68MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 33.66MB |
| 5 | `bufio.NewReaderSize` | 33.14MB |
| 6 | `runtime.mallocgc` | 18.01MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 12.01MB |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 119.05GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 93.73GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 92.87GB |
| 4 | `internal/evaluation.mergeMetadata` | 90.46GB |
| 5 | `reflect.unsafe_NewArray` | 51.53GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.45GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 8 | `experiment/local.topologicalSort` | 46.32GB |
| 9 | `reflect.MakeSlice` | 28.56GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 149/151 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/151 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.65MB | 25/151 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/151 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.57MB | 145/151 | `████░░░░░░░░░░░ 31%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/151 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/151 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/151 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 148/151 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 140/151 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 60.13GB | 142/151 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.3GB | 127/151 | `███████░░░░░░░░ 47%` |
| 3 | `internal/evaluation.mergeMetadata` | 26.13GB | 138/151 | `██████░░░░░░░░░ 43%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 26.05GB | 144/151 | `██████░░░░░░░░░ 43%` |
| 5 | `reflect.unsafe_NewArray` | 25.99GB | 142/151 | `██████░░░░░░░░░ 43%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 25.9GB | 143/151 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 14.66GB | 140/151 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 13.27GB | 139/151 | `███░░░░░░░░░░░░ 22%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.19GB | 140/151 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.32GB | 127/151 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
