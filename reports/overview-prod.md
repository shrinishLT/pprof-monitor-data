# Overview: prod
*Last updated: 2026-05-17 01:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T01:02 (62 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 15,623 | max: 84,644 | trend: decreasing (-122.75/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 168.6MB | avg: 240.7MB | max: 1896.6MB | trend: decreasing (-6.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,072 | -5 | 15,623 | 84,644 | decreasing (-122.75/hr) |
| Heap InUse | 168.6MB | 163.5MB | +5.1MB | 240.7MB | 1896.6MB | decreasing (-6.07MB/hr) |
| Heap Sys | 3472.2MB | 3472.2MB | +0.0MB | 4585.7MB | 5842.7MB | |
| Heap Objects | 1,222,991 | 1,166,939 | +56052 | 1,036,212 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 3 | 14,087 | 159.7MB | 168.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 1.5MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 41.33GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.82GB |
| 3 | `segmentio/kafka-go.makePartitions` | 14.75GB |
| 4 | `internal/evaluation.mergeMetadata` | 14.26GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 8.82GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.75GB |
| 7 | `reflect.unsafe_NewArray` | 7.72GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.39GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.83GB |
| 10 | `experiment/local.topologicalSort` | 5.72GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 60/62 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/62 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/62 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 29.09MB | 60/62 | `███████████░░░░ 79%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/62 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 23.0MB | 9/62 | `█████████░░░░░░ 62%` |
| 7 | `bytes.growSlice` | 18.32MB | 25/62 | `███████░░░░░░░░ 50%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/62 | `██████░░░░░░░░░ 45%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/62 | `██████░░░░░░░░░ 45%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/62 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.94GB | 57/62 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 33.4GB | 51/62 | `█████████░░░░░░ 64%` |
| 3 | `reflect.growslice` | 25.45GB | 23/62 | `███████░░░░░░░░ 48%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/62 | `███████░░░░░░░░ 47%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 19.78GB | 57/62 | `█████░░░░░░░░░░ 38%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 19.63GB | 57/62 | `█████░░░░░░░░░░ 37%` |
| 7 | `jackskj/carta.getUniqueId` | 19.62GB | 17/62 | `█████░░░░░░░░░░ 37%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.09GB | 56/62 | `█████░░░░░░░░░░ 36%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/62 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.84GB | 49/62 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
