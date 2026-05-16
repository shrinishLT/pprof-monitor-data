# Overview: prod
*Last updated: 2026-05-16 14:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T14:32 (41 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,401 | avg: 16,358 | max: 84,644 | trend: decreasing (-96.09/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 132.3MB | avg: 285.6MB | max: 1896.6MB | trend: decreasing (-1.14MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,401 | 14,411 | -10 | 16,358 | 84,644 | decreasing (-96.09/hr) |
| Heap InUse | 132.3MB | 257.3MB | -125.0MB | 285.6MB | 1896.6MB | decreasing (-1.14MB/hr) |
| Heap Sys | 3310.2MB | 5840.8MB | -2530.6MB | 5177.0MB | 5842.7MB | |
| Heap Objects | 500,968 | 1,068,177 | -567209 | 1,121,097 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 31 | 17,018 | 300.5MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 7.0GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 3.22GB |
| 3 | `internal/evaluation.mergeMetadata` | 1.36GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.13GB |
| 5 | `database/sql.convertAssignRows` | 971.04MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 936.98MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 887.92MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 851.26MB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 792.1MB |
| 10 | `segmentio/kafka-go.makePartitions` | 668.68MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 39.03MB | 39/41 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 39/41 | `██████████████░ 93%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/41 | `███████████░░░░ 78%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/41 | `███████████░░░░ 76%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/41 | `███████████░░░░ 73%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/41 | `██████████░░░░░ 69%` |
| 7 | `bytes.growSlice` | 19.45MB | 23/41 | `███████░░░░░░░░ 49%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/41 | `██████░░░░░░░░░ 42%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/41 | `██████░░░░░░░░░ 42%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/41 | `██████░░░░░░░░░ 41%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 66.7GB | 36/41 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 50.2GB | 30/41 | `███████████░░░░ 75%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 27.91GB | 36/41 | `██████░░░░░░░░░ 41%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.73GB | 36/41 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 25.45GB | 23/41 | `█████░░░░░░░░░░ 38%` |
| 6 | `fmt.(*buffer).writeString` | 24.63GB | 15/41 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 23.28GB | 35/41 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 20.74GB | 29/41 | `████░░░░░░░░░░░ 31%` |
| 9 | `jackskj/carta.getUniqueId` | 19.62GB | 17/41 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/41 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.2x avg)
