# Overview: prod
*Last updated: 2026-05-16 00:40 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T00:40 (14 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,942 | avg: 14,462 | max: 15,942 | trend: INCREASING (+125.42/hr))
```
▁▁▁▁▁▂▂▁▁▂▁▃▁█
```

**Heap InUse** (current: 167.2MB | avg: 222.8MB | max: 280.1MB | trend: decreasing (-12.97MB/hr))
```
▆▆▆▄▆█▅▇▅▄▄▅▁▂
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,942 | 14,252 | +1690 | 14,462 | 15,942 | INCREASING (+125.42/hr) |
| Heap InUse | 167.2MB | 124.1MB | +43.1MB | 222.8MB | 280.1MB | decreasing (-12.97MB/hr) |
| Heap Sys | 1453.3MB | 1457.8MB | -4.5MB | 4888.6MB | 5825.3MB | |
| Heap Objects | 387,576 | 509,215 | -121639 | 845,448 | 1,322,856 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 4 | 14,840 | 181.1MB | 222.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.08MB |
| 3 | `bytes.growSlice` | 9.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.48GB |
| 2 | `internal/evaluation.mergeMetadata` | 1.8GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.15GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 1.11GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 1.08GB |
| 6 | `experiment/local.topologicalSort` | 719.58MB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 589.13MB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 588.91MB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 489.61MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 407.51MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 12/14 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.18MB | 12/14 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB | 3/14 | `██░░░░░░░░░░░░░ 16%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB | 1/14 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `bytes.growSlice` | 3.74MB | 5/14 | `█░░░░░░░░░░░░░░ 10%` |
| 6 | `runtime.mallocgc` | 3.5MB | 12/14 | `█░░░░░░░░░░░░░░ 9%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 2.5MB | 2/14 | `█░░░░░░░░░░░░░░ 6%` |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB | 3/14 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.29MB | 10/14 | `░░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 2.29MB | 10/14 | `░░░░░░░░░░░░░░░ 6%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 135.3GB | 9/14 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/14 | `████░░░░░░░░░░░ 32%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/14 | `███░░░░░░░░░░░░ 23%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 30.92GB | 9/14 | `███░░░░░░░░░░░░ 22%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 10.01GB | 9/14 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 10.0GB | 9/14 | `█░░░░░░░░░░░░░░ 7%` |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.57GB | 6/14 | `█░░░░░░░░░░░░░░ 7%` |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/14 | `█░░░░░░░░░░░░░░ 6%` |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/14 | `█░░░░░░░░░░░░░░ 6%` |
| 10 | `compress/flate.NewWriter` | 6.79GB | 9/14 | `░░░░░░░░░░░░░░░ 5%` |

## Alerts

No anomalies detected.
