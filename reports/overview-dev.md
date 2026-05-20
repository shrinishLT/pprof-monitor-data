# Overview: dev
*Last updated: 2026-05-20 20:00 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T20:00 (8 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,055 | avg: 12,611 | max: 14,728 | trend: INCREASING (+2356.86/hr))
```
▁▇▇▇█▇▇▇
```

**Heap InUse** (current: 85.1MB | avg: 96.6MB | max: 141.5MB | trend: INCREASING (+14.76MB/hr))
```
▁▅▇▆█▅▆▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `████████░░░░░░░░░░░░ 43%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,055 | 14,578 | -523 | 12,611 | 14,728 | INCREASING (+2356.86/hr) |
| Heap InUse | 85.1MB | 120.8MB | -35.7MB | 96.6MB | 141.5MB | INCREASING (+14.76MB/hr) |
| Heap Sys | 144.2MB | 193.0MB | -48.8MB | 144.0MB | 196.5MB | |
| Heap Objects | 307,424 | 507,196 | -199772 | 367,187 | 594,424 | |

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
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.77MB | 7/8 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 6/8 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 6.14MB | 7/8 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB | 6/8 | `██░░░░░░░░░░░░░ 16%` |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.38MB | 4/8 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 6/8 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `reflect.mapassign_faststr0` | 2.2MB | 5/8 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `bufio.NewReaderSize` | 2.13MB | 4/8 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `bufio.NewWriterSize` | 2.01MB | 1/8 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.88MB | 4/8 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 180.98MB | 4/8 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 176.53MB | 4/8 | `██████████████░ 97%` |
| 3 | `internal/evaluation.mergeMetadata` | 147.84MB | 5/8 | `████████████░░░ 81%` |
| 4 | `segmentio/kafka-go.makePartitions` | 134.86MB | 2/8 | `███████████░░░░ 74%` |
| 5 | `io.ReadAll` | 129.31MB | 3/8 | `██████████░░░░░ 71%` |
| 6 | `reflect.mapassign_faststr0` | 121.7MB | 3/8 | `██████████░░░░░ 67%` |
| 7 | `net.dnsPacketRoundTrip` | 120.98MB | 3/8 | `██████████░░░░░ 66%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 93.91MB | 4/8 | `███████░░░░░░░░ 51%` |
| 9 | `experiment/local.topologicalSort` | 81.77MB | 4/8 | `██████░░░░░░░░░ 45%` |
| 10 | `net.newRequest` | 77.54MB | 1/8 | `██████░░░░░░░░░ 42%` |

## Alerts

No anomalies detected.
