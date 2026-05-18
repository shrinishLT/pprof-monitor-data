# Overview: stage
*Last updated: 2026-05-18 19:04 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T19:04 (150 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 28,205 | avg: 14,356 | max: 28,205 | trend: INCREASING (+16.57/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█
```

**Heap InUse** (current: 732.9MB | avg: 158.4MB | max: 732.9MB | trend: INCREASING (+0.92MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `█████████░░░░░░░░░░░ 46%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 28,205 | 14,087 | +14118 | 14,356 | 28,205 | INCREASING (+16.57/hr) |
| Heap InUse | 732.9MB | 141.2MB | +591.7MB | 158.4MB | 732.9MB | INCREASING (+0.92MB/hr) |
| Heap Sys | 1592.0MB | 1572.5MB | +19.5MB | 926.1MB | 1592.0MB | |
| Heap Objects | 2,432,873 | 466,632 | +1966241 | 842,296 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 43 | 14,903 | 187.1MB | 732.9MB |

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
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 148/150 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/150 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 12.14MB | 24/150 | `████░░░░░░░░░░░ 33%` |
| 4 | `runtime.mallocgc` | 11.52MB | 144/150 | `████░░░░░░░░░░░ 31%` |
| 5 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/150 | `████░░░░░░░░░░░ 29%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.75MB | 10/150 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 1/150 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 147/150 | `███░░░░░░░░░░░░ 25%` |
| 9 | `bufio.NewReaderSize` | 9.15MB | 14/150 | `███░░░░░░░░░░░░ 24%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 139/150 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 59.71GB | 141/150 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.15GB | 126/150 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 25.81GB | 141/150 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 25.66GB | 137/150 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 25.58GB | 143/150 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 25.43GB | 142/150 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 14.56GB | 139/150 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 13.03GB | 138/150 | `███░░░░░░░░░░░░ 21%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.94GB | 139/150 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.26GB | 126/150 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (4.0x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
