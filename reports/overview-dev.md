# Overview: dev
*Last updated: 2026-05-20 19:29 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T19:29 (7 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,578 | avg: 12,404 | max: 14,728 | trend: INCREASING (+3122.64/hr))
```
▁▇▇▇█▇▇
```

**Heap InUse** (current: 120.8MB | avg: 98.2MB | max: 141.5MB | trend: INCREASING (+25.42MB/hr))
```
▁▅▇▆█▅▆
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `████████████░░░░░░░░ 61%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,578 | 14,042 | +536 | 12,404 | 14,728 | INCREASING (+3122.64/hr) |
| Heap InUse | 120.8MB | 84.2MB | +36.6MB | 98.2MB | 141.5MB | INCREASING (+25.42MB/hr) |
| Heap Sys | 193.0MB | 90.2MB | +102.8MB | 144.0MB | 196.5MB | |
| Heap Objects | 507,196 | 352,703 | +154493 | 375,724 | 594,424 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 37.13MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.0MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 2.51MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.01MB |
| 9 | `experiment/local.(*Client).EvaluateV2` | 1.62MB |
| 10 | `internal/evaluation.(*Engine).Evaluate` | 1.57MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 102.78MB |
| 2 | `internal/evaluation.mergeMetadata` | 94.02MB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 84.97MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 57.78MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 37.13MB |
| 6 | `experiment/local.topologicalSort` | 34.06MB |
| 7 | `reflect.unsafe_New` | 23.01MB |
| 8 | `reflect.growslice` | 22.26MB |
| 9 | `fmt.Sprintf` | 20.55MB |
| 10 | `jackskj/carta.getUniqueId` | 20.0MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.8MB | 6/7 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 5/7 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 6.0MB | 6/7 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.8MB | 5/7 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 5/7 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.17MB | 3/7 | `░░░░░░░░░░░░░░░ 5%` |
| 7 | `bufio.NewReaderSize` | 2.13MB | 4/7 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `reflect.mapassign_faststr0` | 2.12MB | 4/7 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `bufio.NewWriterSize` | 2.01MB | 1/7 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.88MB | 4/7 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `io.ReadAll` | 187.96MB | 2/7 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 180.98MB | 4/7 | `██████████████░ 96%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 176.53MB | 4/7 | `██████████████░ 93%` |
| 4 | `net.dnsPacketRoundTrip` | 174.46MB | 2/7 | `█████████████░░ 92%` |
| 5 | `reflect.mapassign_faststr0` | 173.8MB | 2/7 | `█████████████░░ 92%` |
| 6 | `internal/evaluation.mergeMetadata` | 147.84MB | 5/7 | `███████████░░░░ 78%` |
| 7 | `segmentio/kafka-go.makePartitions` | 134.86MB | 2/7 | `██████████░░░░░ 71%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 93.91MB | 4/7 | `███████░░░░░░░░ 49%` |
| 9 | `experiment/local.topologicalSort` | 81.77MB | 4/7 | `██████░░░░░░░░░ 43%` |
| 10 | `net.newRequest` | 77.54MB | 1/7 | `██████░░░░░░░░░ 41%` |

## Alerts

No anomalies detected.
