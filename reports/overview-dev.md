# Overview: dev
*Last updated: 2026-05-20 18:07 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T18:07 (5 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,728 | avg: 11,642 | max: 14,728 | trend: INCREASING (+6022.00/hr))
```
▁▇▇▇█
```

**Heap InUse** (current: 141.5MB | avg: 96.5MB | max: 141.5MB | trend: INCREASING (+61.52MB/hr))
```
▁▅▇▆█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `██████████████░░░░░░ 72%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,728 | 14,706 | +22 | 11,642 | 14,728 | INCREASING (+6022.00/hr) |
| Heap InUse | 141.5MB | 112.6MB | +28.9MB | 96.5MB | 141.5MB | INCREASING (+61.52MB/hr) |
| Heap Sys | 190.9MB | 191.4MB | -0.5MB | 145.0MB | 196.5MB | |
| Heap Objects | 594,424 | 307,296 | +287128 | 354,034 | 594,424 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.0MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewReaderSize` | 2.01MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `experiment/local.(*Client).EvaluateV2` | 154.69MB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 143.27MB |
| 3 | `internal/evaluation.mergeMetadata` | 127.53MB |
| 4 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 77.44MB |
| 5 | `fmt.Sprintf` | 64.67MB |
| 6 | `experiment/local.topologicalSort` | 59.51MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 27.5MB |
| 9 | `strconv.appendQuotedWith` | 27.08MB |
| 10 | `fmt.Sprint` | 25.08MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4/5 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 4/5 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 6.75MB | 4/5 | `██░░░░░░░░░░░░░ 18%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB | 4/5 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 4/5 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `bufio.NewReaderSize` | 2.18MB | 3/5 | `░░░░░░░░░░░░░░░ 5%` |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.17MB | 3/5 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `bufio.NewWriterSize` | 2.01MB | 1/5 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `reflect.mapassign_faststr0` | 2.0MB | 3/5 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.68MB | 3/5 | `░░░░░░░░░░░░░░░ 4%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 207.05MB | 3/5 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 207.04MB | 3/5 | `██████████████░ 99%` |
| 3 | `io.ReadAll` | 187.96MB | 2/5 | `█████████████░░ 90%` |
| 4 | `net.dnsPacketRoundTrip` | 174.46MB | 2/5 | `████████████░░░ 84%` |
| 5 | `reflect.mapassign_faststr0` | 173.8MB | 2/5 | `████████████░░░ 83%` |
| 6 | `internal/evaluation.mergeMetadata` | 161.29MB | 4/5 | `███████████░░░░ 77%` |
| 7 | `segmentio/kafka-go.makePartitions` | 134.86MB | 2/5 | `█████████░░░░░░ 65%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 105.95MB | 3/5 | `███████░░░░░░░░ 51%` |
| 9 | `experiment/local.topologicalSort` | 97.68MB | 3/5 | `███████░░░░░░░░ 47%` |
| 10 | `reflect.unsafe_New` | 87.0MB | 2/5 | `██████░░░░░░░░░ 42%` |

## Alerts

No anomalies detected.
