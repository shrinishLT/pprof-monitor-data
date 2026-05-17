# Overview: prod
*Last updated: 2026-05-17 14:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T14:31 (89 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,751 | avg: 15,494 | max: 84,644 | trend: decreasing (-50.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 273.4MB | avg: 227.2MB | max: 1896.6MB | trend: decreasing (-3.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,751 | 15,378 | -627 | 15,494 | 84,644 | decreasing (-50.30/hr) |
| Heap InUse | 273.4MB | 197.2MB | +76.2MB | 227.2MB | 1896.6MB | decreasing (-3.11MB/hr) |
| Heap Sys | 2763.3MB | 565.1MB | +2198.2MB | 4257.1MB | 5842.7MB | |
| Heap Objects | 1,655,642 | 934,273 | +721369 | 992,215 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 30 | 15,085 | 192.4MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 39.27MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 28.0MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `runtime.mallocgc` | 8.58MB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 8.12MB |
| 7 | `bufio.NewWriterSize` | 5.02MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `bufio.NewReaderSize` | 3.03MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 8.75GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 7.24GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 5.25GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 5.23GB |
| 5 | `experiment/local.topologicalSort` | 3.54GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 3.37GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.64GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 1.64GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.2GB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.05GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 87/89 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/89 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/89 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.24MB | 87/89 | `██████████░░░░░ 68%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/89 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/89 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 14.97MB | 43/89 | `██████░░░░░░░░░ 40%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.39MB | 20/89 | `█████░░░░░░░░░░ 36%` |
| 9 | `crypto/tls.Client` | 13.01MB | 3/89 | `█████░░░░░░░░░░ 35%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/89 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.94GB | 82/89 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.41GB | 78/89 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/89 | `██████░░░░░░░░░ 43%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.6GB | 80/89 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/89 | `█████░░░░░░░░░░ 36%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.28GB | 84/89 | `████░░░░░░░░░░░ 32%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.15GB | 84/89 | `████░░░░░░░░░░░ 32%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/89 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/89 | `████░░░░░░░░░░░ 28%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.99GB | 34/89 | `████░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
