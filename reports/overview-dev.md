# Overview: dev
*Last updated: 2026-05-20 20:00 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T20:00 (9 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,055 | avg: 12,771 | max: 14,728 | trend: INCREASING (+1842.37/hr))
```
▁▇▇▇█▇▇▇▇
```

**Heap InUse** (current: 91.0MB | avg: 96.0MB | max: 141.5MB | trend: INCREASING (+9.59MB/hr))
```
▁▅▇▆█▅▆▅▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `█████████░░░░░░░░░░░ 46%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,055 | 14,055 | +0 | 12,771 | 14,728 | INCREASING (+1842.37/hr) |
| Heap InUse | 91.0MB | 85.1MB | +5.9MB | 96.0MB | 141.5MB | INCREASING (+9.59MB/hr) |
| Heap Sys | 144.2MB | 144.2MB | +0.0MB | 144.1MB | 196.5MB | |
| Heap Objects | 426,669 | 307,424 | +119245 | 373,796 | 594,424 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.0MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `kafka-go/protocol.structDecodeFuncOf.func1.1` | 1.0MB |
| 10 | `jasonlvhit/gocron.NewScheduler` | 553.04kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `reflect.mapassign_faststr0` | 17.5MB |
| 3 | `net.dnsPacketRoundTrip` | 14.02MB |
| 4 | `fmt.Sprintf` | 12.02MB |
| 5 | `io.ReadAll` | 12.0MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `reflect.growslice` | 9.22MB |
| 8 | `strconv.appendQuotedWith` | 8.52MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 10 | `reflect.unsafe_New` | 8.0MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.76MB | 8/9 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 7/9 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 6.25MB | 8/9 | `██░░░░░░░░░░░░░ 17%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.14MB | 7/9 | `██░░░░░░░░░░░░░ 16%` |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB | 5/9 | `█░░░░░░░░░░░░░░ 6%` |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 7/9 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `reflect.mapassign_faststr0` | 2.25MB | 6/9 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `bufio.NewReaderSize` | 2.13MB | 4/9 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `bufio.NewWriterSize` | 2.01MB | 1/9 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.88MB | 4/9 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 180.98MB | 4/9 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 176.53MB | 4/9 | `██████████████░ 97%` |
| 3 | `internal/evaluation.mergeMetadata` | 147.84MB | 5/9 | `████████████░░░ 81%` |
| 4 | `segmentio/kafka-go.makePartitions` | 134.86MB | 2/9 | `███████████░░░░ 74%` |
| 5 | `io.ReadAll` | 99.98MB | 4/9 | `████████░░░░░░░ 55%` |
| 6 | `reflect.mapassign_faststr0` | 95.65MB | 4/9 | `███████░░░░░░░░ 52%` |
| 7 | `net.dnsPacketRoundTrip` | 94.24MB | 4/9 | `███████░░░░░░░░ 52%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 93.91MB | 4/9 | `███████░░░░░░░░ 51%` |
| 9 | `experiment/local.topologicalSort` | 81.77MB | 4/9 | `██████░░░░░░░░░ 45%` |
| 10 | `net.newRequest` | 77.54MB | 1/9 | `██████░░░░░░░░░ 42%` |

## Alerts

No anomalies detected.
