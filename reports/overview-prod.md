# Overview: prod
*Last updated: 2026-05-18 04:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T04:32 (117 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,069 | avg: 15,206 | max: 84,644 | trend: decreasing (-44.98/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 114.4MB | avg: 206.7MB | max: 1896.6MB | trend: decreasing (-2.98MB/hr))
```
▃▄▅█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,069 | 14,263 | -194 | 15,206 | 84,644 | decreasing (-44.98/hr) |
| Heap InUse | 114.4MB | 125.9MB | -11.5MB | 206.7MB | 1896.6MB | decreasing (-2.98MB/hr) |
| Heap Sys | 4699.3MB | 4699.2MB | +0.1MB | 4152.1MB | 5842.7MB | |
| Heap Objects | 505,265 | 454,718 | +50547 | 918,672 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 10 | 14,237 | 135.2MB | 156.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.45GB |
| 2 | `internal/evaluation.mergeMetadata` | 68.83GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 41.5GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 41.47GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 31.73GB |
| 6 | `experiment/local.topologicalSort` | 27.48GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.94GB |
| 8 | `segmentio/kafka-go.makePartitions` | 17.58GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 13.13GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.16GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 115/117 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/117 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/117 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.19MB | 115/117 | `████████░░░░░░░ 57%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/117 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/117 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/117 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 13.0MB | 52/117 | `█████░░░░░░░░░░ 35%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/117 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.7MB | 24/117 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.5GB | 110/117 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.78GB | 106/117 | `█████████░░░░░░ 61%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/117 | `███████░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.29GB | 108/117 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/117 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.05GB | 112/117 | `█████░░░░░░░░░░ 36%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.97GB | 112/117 | `█████░░░░░░░░░░ 36%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/117 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/117 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 13.06GB | 94/117 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
