# Overview: prod
*Last updated: 2026-05-16 01:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T01:31 (16 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,140 | avg: 14,426 | max: 15,942 | trend: INCREASING (+59.96/hr))
```
▁▁▁▁▁▂▂▁▁▂▁▃▁█▁▁
```

**Heap InUse** (current: 134.7MB | avg: 212.9MB | max: 280.1MB | trend: decreasing (-15.27MB/hr))
```
▆▆▆▄▆█▅▇▅▄▄▅▁▂▂▁
```

## Current Status

Goroutines: `█████████████████░░░ 88%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,140 | 14,208 | -68 | 14,426 | 15,942 | INCREASING (+59.96/hr) |
| Heap InUse | 134.7MB | 152.0MB | -17.3MB | 212.9MB | 280.1MB | decreasing (-15.27MB/hr) |
| Heap Sys | 3683.5MB | 1391.0MB | +2292.5MB | 4594.6MB | 5825.3MB | |
| Heap Objects | 377,899 | 552,073 | -174174 | 797,890 | 1,322,856 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 6 | 14,618 | 168.5MB | 222.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 21.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `kafka-go/protocol.newPage` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 28.45GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 17.28GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 17.19GB |
| 4 | `experiment/local.topologicalSort` | 11.46GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.94GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 7.04GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.63GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 5.37GB |
| 9 | `fmt.Sprintf` | 4.22GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 3.23GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 14/16 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.19MB | 14/16 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB | 5/16 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `runtime.mallocgc` | 6.0MB | 14/16 | `██░░░░░░░░░░░░░ 16%` |
| 5 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.61MB | 1/16 | `██░░░░░░░░░░░░░ 15%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB | 1/16 | `██░░░░░░░░░░░░░ 15%` |
| 7 | `bytes.growSlice` | 3.45MB | 6/16 | `█░░░░░░░░░░░░░░ 9%` |
| 8 | `reflect.mapassign_faststr0` | 3.0MB | 1/16 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB | 2/16 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB | 5/16 | `█░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 111.56GB | 11/16 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/16 | `█████░░░░░░░░░░ 39%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/16 | `████░░░░░░░░░░░ 28%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 28.15GB | 10/16 | `███░░░░░░░░░░░░ 25%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 10.87GB | 11/16 | `█░░░░░░░░░░░░░░ 9%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 10.85GB | 11/16 | `█░░░░░░░░░░░░░░ 9%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.53GB | 5/16 | `█░░░░░░░░░░░░░░ 9%` |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/16 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/16 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 8.1GB | 8/16 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

No anomalies detected.
