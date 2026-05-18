# Overview: prod
*Last updated: 2026-05-18 07:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T07:33 (123 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,702 | avg: 15,185 | max: 84,644 | trend: decreasing (-40.69/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 129.2MB | avg: 207.0MB | max: 1896.6MB | trend: decreasing (-2.54MB/hr))
```
▄▄▃▄▆▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,702 | 14,573 | +129 | 15,185 | 84,644 | decreasing (-40.69/hr) |
| Heap InUse | 129.2MB | 156.6MB | -27.4MB | 207.0MB | 1896.6MB | decreasing (-2.54MB/hr) |
| Heap Sys | 4699.5MB | 4699.4MB | +0.1MB | 4178.7MB | 5842.7MB | |
| Heap Objects | 308,835 | 737,374 | -428539 | 924,741 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 16 | 14,438 | 164.2MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 9 | `bufio.NewReaderSize` | 1.51MB |
| 10 | `bufio.NewWriterSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 121.0GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 106.63GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 73.31GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 73.06GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 48.71GB |
| 6 | `experiment/local.topologicalSort` | 48.31GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 37.36GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 23.18GB |
| 9 | `segmentio/kafka-go.makePartitions` | 21.45GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.07GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/123 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 121/123 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/123 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.56MB | 121/123 | `████████░░░░░░░ 55%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/123 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/123 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/123 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.23MB | 57/123 | `████░░░░░░░░░░░ 33%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/123 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.35MB | 28/123 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.54GB | 116/123 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 35.83GB | 112/123 | `██████████░░░░░ 66%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/123 | `██████░░░░░░░░░ 45%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.35GB | 114/123 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.38GB | 118/123 | `█████░░░░░░░░░░ 39%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.31GB | 118/123 | `█████░░░░░░░░░░ 39%` |
| 7 | `reflect.growslice` | 20.37GB | 36/123 | `█████░░░░░░░░░░ 38%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/123 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/123 | `████░░░░░░░░░░░ 29%` |
| 10 | `experiment/local.topologicalSort` | 14.84GB | 100/123 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
