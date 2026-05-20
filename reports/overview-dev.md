# Overview: dev
*Last updated: 2026-05-20 17:32 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T17:32 (3 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,725 | avg: 9,592 | max: 14,725 | trend: stable (+0.00/hr))
```
▁▇█
```

**Heap InUse** (current: 140.4MB | avg: 76.1MB | max: 140.4MB | trend: stable (+0.00MB/hr))
```
▁▅█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `██████████████░░░░░░ 71%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,725 | 14,052 | +673 | 9,592 | 14,725 | stable (+0.00/hr) |
| Heap InUse | 140.4MB | 88.0MB | +52.4MB | 76.1MB | 140.4MB | stable (+0.00MB/hr) |
| Heap Sys | 196.5MB | 146.1MB | +50.4MB | 114.2MB | 196.5MB | |
| Heap Objects | 536,577 | 331,873 | +204704 | 289,483 | 536,577 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 4 | `runtime.mallocgc` | 4.5MB |
| 5 | `bufio.NewReaderSize` | 2.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.01MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 1.55MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 10 | `aws/endpoints.init` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 409.1MB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 396.13MB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 379.3MB |
| 4 | `experiment/local.topologicalSort` | 197.92MB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 193.9MB |
| 6 | `io.ReadAll` | 193.29MB |
| 7 | `net.dnsPacketRoundTrip` | 181.22MB |
| 8 | `reflect.mapassign_faststr0` | 180.05MB |
| 9 | `segmentio/kafka-go.makePartitions` | 138.11MB |
| 10 | `reflect.unsafe_New` | 90.0MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2/3 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 2/3 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB | 2/3 | `██░░░░░░░░░░░░░ 17%` |
| 4 | `runtime.mallocgc` | 4.5MB | 2/3 | `█░░░░░░░░░░░░░░ 12%` |
| 5 | `bufio.NewReaderSize` | 2.51MB | 1/3 | `█░░░░░░░░░░░░░░ 6%` |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 2/3 | `░░░░░░░░░░░░░░░ 6%` |
| 7 | `bytes.growSlice` | 2.01MB | 1/3 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 1.55MB | 1/3 | `░░░░░░░░░░░░░░░ 4%` |
| 9 | `aws/endpoints.init` | 1.51MB | 2/3 | `░░░░░░░░░░░░░░░ 4%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB | 1/3 | `░░░░░░░░░░░░░░░ 4%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 396.13MB | 1/3 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 379.3MB | 1/3 | `██████████████░ 95%` |
| 3 | `internal/evaluation.mergeMetadata` | 222.81MB | 2/3 | `████████░░░░░░░ 56%` |
| 4 | `experiment/local.topologicalSort` | 197.92MB | 1/3 | `███████░░░░░░░░ 49%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 193.9MB | 1/3 | `███████░░░░░░░░ 48%` |
| 6 | `io.ReadAll` | 187.96MB | 2/3 | `███████░░░░░░░░ 47%` |
| 7 | `net.dnsPacketRoundTrip` | 174.46MB | 2/3 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.mapassign_faststr0` | 173.8MB | 2/3 | `██████░░░░░░░░░ 43%` |
| 9 | `segmentio/kafka-go.makePartitions` | 134.86MB | 2/3 | `█████░░░░░░░░░░ 34%` |
| 10 | `reflect.unsafe_New` | 87.0MB | 2/3 | `███░░░░░░░░░░░░ 21%` |

## Alerts

No anomalies detected.
