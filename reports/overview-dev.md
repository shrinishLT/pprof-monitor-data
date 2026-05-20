# Overview: dev
*Last updated: 2026-05-20 17:58 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T17:57 (4 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,706 | avg: 10,871 | max: 14,725 | trend: INCREASING (+8958.20/hr))
```
▁▇█▇
```

**Heap InUse** (current: 112.6MB | avg: 85.2MB | max: 140.4MB | trend: INCREASING (+78.04MB/hr))
```
▁▅█▆
```

## Current Status

Goroutines: `███████████████████░ 99%`
Heap InUse: `███████████░░░░░░░░░ 57%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,706 | 14,725 | -19 | 10,871 | 14,725 | INCREASING (+8958.20/hr) |
| Heap InUse | 112.6MB | 140.4MB | -27.8MB | 85.2MB | 140.4MB | INCREASING (+78.04MB/hr) |
| Heap Sys | 191.4MB | 196.5MB | -5.1MB | 133.5MB | 196.5MB | |
| Heap Objects | 307,296 | 536,577 | -229281 | 293,936 | 536,577 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.0MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `reflect.mapassign_faststr0` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.01MB |
| 9 | `bufio.NewWriterSize` | 2.01MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `experiment/local.(*Client).EvaluateV2` | 87.14MB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 81.75MB |
| 3 | `internal/evaluation.mergeMetadata` | 72.02MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.52MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `experiment/local.topologicalSort` | 35.6MB |
| 7 | `fmt.Sprintf` | 34.61MB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 16.0MB |
| 9 | `fmt.Sprint` | 14.55MB |
| 10 | `strconv.appendQuotedWith` | 14.04MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3/4 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 3/4 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 6.0MB | 3/4 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.83MB | 3/4 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 3/4 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `bufio.NewReaderSize` | 2.26MB | 2/4 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `bufio.NewWriterSize` | 2.01MB | 1/4 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB | 2/4 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `reflect.mapassign_faststr0` | 2.0MB | 2/4 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.76MB | 2/4 | `░░░░░░░░░░░░░░░ 4%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 238.94MB | 2/4 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 233.22MB | 2/4 | `██████████████░ 97%` |
| 3 | `io.ReadAll` | 187.96MB | 2/4 | `███████████░░░░ 78%` |
| 4 | `net.dnsPacketRoundTrip` | 174.46MB | 2/4 | `██████████░░░░░ 73%` |
| 5 | `reflect.mapassign_faststr0` | 173.8MB | 2/4 | `██████████░░░░░ 72%` |
| 6 | `internal/evaluation.mergeMetadata` | 172.54MB | 3/4 | `██████████░░░░░ 72%` |
| 7 | `segmentio/kafka-go.makePartitions` | 134.86MB | 2/4 | `████████░░░░░░░ 56%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 120.21MB | 2/4 | `███████░░░░░░░░ 50%` |
| 9 | `experiment/local.topologicalSort` | 116.76MB | 2/4 | `███████░░░░░░░░ 48%` |
| 10 | `reflect.unsafe_New` | 87.0MB | 2/4 | `█████░░░░░░░░░░ 36%` |

## Alerts

No anomalies detected.
