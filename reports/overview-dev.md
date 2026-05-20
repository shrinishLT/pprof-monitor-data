# Overview: dev
*Last updated: 2026-05-20 17:16 IST*
*Data range: 2026-05-20T17:14 to 2026-05-20T17:15 (2 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,052 | avg: 7,026 | max: 14,052 | trend: stable (+0.00/hr))
```
▁█
```

**Heap InUse** (current: 88.0MB | avg: 44.0MB | max: 88.0MB | trend: stable (+0.00MB/hr))
```
▁█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `████████████░░░░░░░░ 60%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,052 | 0 | +14052 | 7,026 | 14,052 | stable (+0.00/hr) |
| Heap InUse | 88.0MB | 0.0MB | +88.0MB | 44.0MB | 88.0MB | stable (+0.00MB/hr) |
| Heap Sys | 146.1MB | 0.0MB | +146.1MB | 73.0MB | 146.1MB | |
| Heap Objects | 331,873 | 0 | +331873 | 165,936 | 331,873 | |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 4 | `runtime.mallocgc` | 4.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `aws/endpoints.init` | 1.51MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |
| 8 | `jasonlvhit/gocron.NewScheduler` | 1.08MB |
| 9 | `reflect.mapassign_faststr0` | 1.0MB |
| 10 | `kafka-go/protocol.newPage` | 544.67kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `io.ReadAll` | 182.63MB |
| 2 | `net.dnsPacketRoundTrip` | 167.7MB |
| 3 | `reflect.mapassign_faststr0` | 167.54MB |
| 4 | `segmentio/kafka-go.makePartitions` | 131.6MB |
| 5 | `reflect.unsafe_New` | 84.0MB |
| 6 | `net.newRequest` | 77.54MB |
| 7 | `reflect.growslice` | 54.03MB |
| 8 | `encoding/json.(*decodeState).literalStore` | 40.0MB |
| 9 | `internal/audit.InitAuditLogWorkerPool.func1` | 37.13MB |
| 10 | `internal/evaluation.mergeMetadata` | 36.51MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1/2 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1/2 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB | 1/2 | `██░░░░░░░░░░░░░ 17%` |
| 4 | `runtime.mallocgc` | 4.5MB | 1/2 | `█░░░░░░░░░░░░░░ 12%` |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB | 1/2 | `░░░░░░░░░░░░░░░ 6%` |
| 6 | `aws/endpoints.init` | 1.51MB | 1/2 | `░░░░░░░░░░░░░░░ 4%` |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB | 1/2 | `░░░░░░░░░░░░░░░ 4%` |
| 8 | `jasonlvhit/gocron.NewScheduler` | 1.08MB | 1/2 | `░░░░░░░░░░░░░░░ 2%` |
| 9 | `reflect.mapassign_faststr0` | 1.0MB | 1/2 | `░░░░░░░░░░░░░░░ 2%` |
| 10 | `kafka-go/protocol.newPage` | 544.67kB | 1/2 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `io.ReadAll` | 182.63MB | 1/2 | `███████████████ 100%` |
| 2 | `net.dnsPacketRoundTrip` | 167.7MB | 1/2 | `█████████████░░ 91%` |
| 3 | `reflect.mapassign_faststr0` | 167.54MB | 1/2 | `█████████████░░ 91%` |
| 4 | `segmentio/kafka-go.makePartitions` | 131.6MB | 1/2 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_New` | 84.0MB | 1/2 | `██████░░░░░░░░░ 45%` |
| 6 | `net.newRequest` | 77.54MB | 1/2 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.growslice` | 54.03MB | 1/2 | `████░░░░░░░░░░░ 29%` |
| 8 | `encoding/json.(*decodeState).literalStore` | 40.0MB | 1/2 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/audit.InitAuditLogWorkerPool.func1` | 37.13MB | 1/2 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 36.51MB | 1/2 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

No anomalies detected.
