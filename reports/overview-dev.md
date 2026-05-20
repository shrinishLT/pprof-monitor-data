# Overview: dev
*Last updated: 2026-05-20 20:52 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T20:52 (11 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,197 | avg: 13,017 | max: 14,728 | trend: INCREASING (+1227.47/hr))
```
▁▇▇▇█▇▇▇▇▇▇
```

**Heap InUse** (current: 98.9MB | avg: 95.2MB | max: 141.5MB | trend: INCREASING (+4.69MB/hr))
```
▁▅▇▆█▅▆▅▅▅▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `██████████░░░░░░░░░░ 50%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,197 | 14,049 | +148 | 13,017 | 14,728 | INCREASING (+1227.47/hr) |
| Heap InUse | 98.9MB | 84.9MB | +14.0MB | 95.2MB | 141.5MB | INCREASING (+4.69MB/hr) |
| Heap Sys | 143.9MB | 144.7MB | -0.8MB | 144.1MB | 196.5MB | |
| Heap Objects | 335,949 | 303,998 | +31951 | 364,010 | 594,424 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.0MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 1.5MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `kafka-go/protocol.structDecodeFuncOf.func1.1` | 1.0MB |
| 10 | `jasonlvhit/gocron.NewScheduler` | 553.04kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `io.ReadAll` | 50.03MB |
| 2 | `reflect.mapassign_faststr0` | 48.51MB |
| 3 | `net.dnsPacketRoundTrip` | 41.55MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `segmentio/kafka-go.makePartitions` | 29.02MB |
| 6 | `reflect.unsafe_New` | 25.0MB |
| 7 | `reflect.growslice` | 19.22MB |
| 8 | `reflect.unsafe_NewArray` | 14.04MB |
| 9 | `net.newRequest` | 13.01MB |
| 10 | `fmt.Sprintf` | 12.02MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.73MB | 10/11 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 9/11 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 6.4MB | 10/11 | `██░░░░░░░░░░░░░ 17%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.33MB | 9/11 | `██░░░░░░░░░░░░░ 17%` |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.64MB | 7/11 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 9/11 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `reflect.mapassign_faststr0` | 2.19MB | 8/11 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `bufio.NewReaderSize` | 2.13MB | 4/11 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `bufio.NewWriterSize` | 2.01MB | 1/11 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.88MB | 4/11 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 180.98MB | 4/11 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 176.53MB | 4/11 | `██████████████░ 97%` |
| 3 | `internal/evaluation.mergeMetadata` | 147.84MB | 5/11 | `████████████░░░ 81%` |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 93.91MB | 4/11 | `███████░░░░░░░░ 51%` |
| 5 | `io.ReadAll` | 82.89MB | 6/11 | `██████░░░░░░░░░ 45%` |
| 6 | `experiment/local.topologicalSort` | 81.77MB | 4/11 | `██████░░░░░░░░░ 45%` |
| 7 | `segmentio/kafka-go.makePartitions` | 81.56MB | 4/11 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.mapassign_faststr0` | 79.6MB | 6/11 | `██████░░░░░░░░░ 43%` |
| 9 | `net.dnsPacketRoundTrip` | 76.51MB | 6/11 | `██████░░░░░░░░░ 42%` |
| 10 | `encoding/json.(*decodeState).literalStore` | 40.0MB | 1/11 | `███░░░░░░░░░░░░ 22%` |

## Alerts

No anomalies detected.
