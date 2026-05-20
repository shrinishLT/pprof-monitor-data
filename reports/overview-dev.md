# Overview: dev
*Last updated: 2026-05-20 19:21 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T19:21 (6 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,042 | avg: 12,042 | max: 14,728 | trend: INCREASING (+4126.80/hr))
```
▁▇▇▇█▇
```

**Heap InUse** (current: 84.2MB | avg: 94.5MB | max: 141.5MB | trend: INCREASING (+31.64MB/hr))
```
▁▅▇▆█▅
```

## Current Status

Goroutines: `███████████████████░ 95%`
Heap InUse: `████████░░░░░░░░░░░░ 42%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,042 | 14,728 | -686 | 12,042 | 14,728 | INCREASING (+4126.80/hr) |
| Heap InUse | 84.2MB | 141.5MB | -57.3MB | 94.5MB | 141.5MB | INCREASING (+31.64MB/hr) |
| Heap Sys | 90.2MB | 190.9MB | -100.7MB | 135.8MB | 196.5MB | |
| Heap Objects | 352,703 | 594,424 | -241721 | 353,812 | 594,424 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 37.13MB |
| 2 | `runtime.mallocgc` | 2.0MB |
| 3 | `internal/audit.auditWorker` | 1.0MB |
| 4 | `aws/endpoints.init` | 512.07kB |
| 5 | `kafka-go/protocol.structEncodeFuncOf` | 512.01kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 37.13MB |
| 2 | `runtime.mallocgc` | 2.0MB |
| 3 | `internal/audit.auditWorker` | 1.0MB |
| 4 | `net.open` | 544.67kB |
| 5 | `internal/filedesc.(*Message).unmarshalFull` | 512.19kB |
| 6 | `aws/endpoints.init` | 512.07kB |
| 7 | `kafka-go/protocol.structEncodeFuncOf` | 512.01kB |
| 8 | `sync.(*Pool).pinSlow` | 512.0kB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.73MB | 5/6 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 4/6 | `███░░░░░░░░░░░░ 25%` |
| 3 | `runtime.mallocgc` | 5.8MB | 5/6 | `██░░░░░░░░░░░░░ 15%` |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB | 4/6 | `██░░░░░░░░░░░░░ 14%` |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 4/6 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `bufio.NewReaderSize` | 2.18MB | 3/6 | `░░░░░░░░░░░░░░░ 5%` |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.17MB | 3/6 | `░░░░░░░░░░░░░░░ 5%` |
| 8 | `bufio.NewWriterSize` | 2.01MB | 1/6 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `reflect.mapassign_faststr0` | 2.0MB | 3/6 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.68MB | 3/6 | `░░░░░░░░░░░░░░░ 4%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.(*Engine).Evaluate` | 207.05MB | 3/6 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 207.04MB | 3/6 | `██████████████░ 99%` |
| 3 | `io.ReadAll` | 187.96MB | 2/6 | `█████████████░░ 90%` |
| 4 | `net.dnsPacketRoundTrip` | 174.46MB | 2/6 | `████████████░░░ 84%` |
| 5 | `reflect.mapassign_faststr0` | 173.8MB | 2/6 | `████████████░░░ 83%` |
| 6 | `internal/evaluation.mergeMetadata` | 161.29MB | 4/6 | `███████████░░░░ 77%` |
| 7 | `segmentio/kafka-go.makePartitions` | 134.86MB | 2/6 | `█████████░░░░░░ 65%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 105.95MB | 3/6 | `███████░░░░░░░░ 51%` |
| 9 | `experiment/local.topologicalSort` | 97.68MB | 3/6 | `███████░░░░░░░░ 47%` |
| 10 | `reflect.unsafe_New` | 87.0MB | 2/6 | `██████░░░░░░░░░ 42%` |

## Alerts

No anomalies detected.
