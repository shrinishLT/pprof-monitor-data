# Overview: prod
*Last updated: 2026-05-17 10:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T10:03 (80 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 27,990 | avg: 15,538 | max: 84,644 | trend: decreasing (-61.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 391.4MB | avg: 226.3MB | max: 1896.6MB | trend: decreasing (-4.39MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 33%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 27,990 | 14,670 | +13320 | 15,538 | 84,644 | decreasing (-61.73/hr) |
| Heap InUse | 391.4MB | 183.4MB | +208.0MB | 226.3MB | 1896.6MB | decreasing (-4.39MB/hr) |
| Heap Sys | 4086.8MB | 4131.0MB | -44.2MB | 4427.1MB | 5842.7MB | |
| Heap Objects | 990,226 | 959,581 | +30645 | 992,192 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 21 | 15,077 | 174.1MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 71.85MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.63MB |
| 4 | `bufio.NewReaderSize` | 27.61MB |
| 5 | `bufio.NewWriterSize` | 23.59MB |
| 6 | `runtime.mallocgc` | 14.51MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 13.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).tryPutIdleConn` | 6.5MB |
| 10 | `crypto/tls.Client` | 6.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 97.51GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.46GB |
| 3 | `internal/evaluation.mergeMetadata` | 35.01GB |
| 4 | `segmentio/kafka-go.makePartitions` | 27.12GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.33GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.19GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 17.12GB |
| 8 | `jackskj/carta.getUniqueId` | 14.95GB |
| 9 | `reflect.growslice` | 14.33GB |
| 10 | `experiment/local.topologicalSort` | 14.04GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 78/80 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/80 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/80 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 24.96MB | 78/80 | `██████████░░░░░ 68%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/80 | `███████░░░░░░░░ 50%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.78MB | 15/80 | `██████░░░░░░░░░ 45%` |
| 7 | `bytes.growSlice` | 16.34MB | 35/80 | `██████░░░░░░░░░ 44%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/80 | `██████░░░░░░░░░ 44%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/80 | `█████░░░░░░░░░░ 36%` |
| 10 | `database/sql.convertAssignRows` | 13.33MB | 6/80 | `█████░░░░░░░░░░ 36%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.83GB | 75/80 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.8GB | 69/80 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/80 | `██████░░░░░░░░░ 43%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.46GB | 74/80 | `█████░░░░░░░░░░ 39%` |
| 5 | `reflect.growslice` | 22.19GB | 30/80 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.48GB | 75/80 | `████░░░░░░░░░░░ 32%` |
| 7 | `jackskj/carta.getUniqueId` | 18.44GB | 20/80 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.35GB | 75/80 | `████░░░░░░░░░░░ 32%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/80 | `████░░░░░░░░░░░ 29%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.8GB | 40/80 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
