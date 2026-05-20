# Overview: dev
*Last updated: 2026-05-20 20:48 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T20:48 (10 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,049 | avg: 12,899 | max: 14,728 | trend: INCREASING (+1479.30/hr))
```
▁▇▇▇█▇▇▇▇▇
```

**Heap InUse** (current: 84.9MB | avg: 94.8MB | max: 141.5MB | trend: INCREASING (+5.77MB/hr))
```
▁▅▇▆█▅▆▅▅▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `████████░░░░░░░░░░░░ 43%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,049 | 14,055 | -6 | 12,899 | 14,728 | INCREASING (+1479.30/hr) |
| Heap InUse | 84.9MB | 91.0MB | -6.1MB | 94.8MB | 141.5MB | INCREASING (+5.77MB/hr) |
| Heap Sys | 144.7MB | 144.2MB | +0.5MB | 144.1MB | 196.5MB | |
| Heap Objects | 303,998 | 426,669 | -122671 | 366,816 | 594,424 | |

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
| 1 | `io.ReadAll` | 47.39MB |
| 2 | `reflect.mapassign_faststr0` | 46.51MB |
| 3 | `net.dnsPacketRoundTrip` | 40.55MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `segmentio/kafka-go.makePartitions` | 27.52MB |
| 6 | `reflect.unsafe_New` | 24.0MB |
| 7 | `reflect.growslice` | 18.22MB |
| 8 | `reflect.unsafe_NewArray` | 13.54MB |
| 9 | `net.newRequest` | 12.51MB |
| 10 | `fmt.Sprintf` | 12.02MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.74MB | 9/10 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 8/10 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 6.33MB | 9/10 | `██░░░░░░░░░░░░░ 17%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.25MB | 8/10 | `██░░░░░░░░░░░░░ 17%` |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.58MB | 6/10 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 8/10 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `reflect.mapassign_faststr0` | 2.29MB | 7/10 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `bufio.NewReaderSize` | 2.13MB | 4/10 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `bufio.NewWriterSize` | 2.01MB | 1/10 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.88MB | 4/10 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 180.98MB | 4/10 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 176.53MB | 4/10 | `██████████████░ 97%` |
| 3 | `internal/evaluation.mergeMetadata` | 147.84MB | 5/10 | `████████████░░░ 81%` |
| 4 | `segmentio/kafka-go.makePartitions` | 99.08MB | 3/10 | `████████░░░░░░░ 54%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 93.91MB | 4/10 | `███████░░░░░░░░ 51%` |
| 6 | `io.ReadAll` | 89.46MB | 5/10 | `███████░░░░░░░░ 49%` |
| 7 | `reflect.mapassign_faststr0` | 85.82MB | 5/10 | `███████░░░░░░░░ 47%` |
| 8 | `net.dnsPacketRoundTrip` | 83.5MB | 5/10 | `██████░░░░░░░░░ 46%` |
| 9 | `experiment/local.topologicalSort` | 81.77MB | 4/10 | `██████░░░░░░░░░ 45%` |
| 10 | `net.newRequest` | 45.03MB | 2/10 | `███░░░░░░░░░░░░ 24%` |

## Alerts

No anomalies detected.
