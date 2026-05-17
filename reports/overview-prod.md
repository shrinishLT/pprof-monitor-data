# Overview: prod
*Last updated: 2026-05-17 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T10:31 (81 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,146 | avg: 15,533 | max: 84,644 | trend: decreasing (-60.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 346.5MB | avg: 227.8MB | max: 1896.6MB | trend: decreasing (-4.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,146 | 27,990 | -12844 | 15,533 | 84,644 | decreasing (-60.18/hr) |
| Heap InUse | 346.5MB | 391.4MB | -44.9MB | 227.8MB | 1896.6MB | decreasing (-4.02MB/hr) |
| Heap Sys | 4083.6MB | 4086.8MB | -3.2MB | 4422.8MB | 5842.7MB | |
| Heap Objects | 1,459,858 | 990,226 | +469632 | 997,966 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 22 | 15,080 | 182.0MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 57.81MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.99MB |
| 7 | `bufio.NewReaderSize` | 3.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 9 | `bufio.NewWriterSize` | 2.51MB |
| 10 | `reflect.unsafe_NewArray` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 97.54GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.48GB |
| 3 | `internal/evaluation.mergeMetadata` | 38.47GB |
| 4 | `segmentio/kafka-go.makePartitions` | 27.76GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 23.4GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 23.22GB |
| 7 | `jackskj/carta.getUniqueId` | 20.07GB |
| 8 | `reflect.growslice` | 19.22GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.02GB |
| 10 | `fmt.(*buffer).writeString` | 16.65GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 79/81 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/81 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/81 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.38MB | 79/81 | `██████████░░░░░ 69%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/81 | `███████░░░░░░░░ 50%` |
| 6 | `bytes.growSlice` | 16.09MB | 36/81 | `██████░░░░░░░░░ 43%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.89MB | 16/81 | `██████░░░░░░░░░ 43%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/81 | `█████░░░░░░░░░░ 36%` |
| 9 | `database/sql.convertAssignRows` | 13.33MB | 6/81 | `█████░░░░░░░░░░ 36%` |
| 10 | `crypto/tls.Client` | 13.01MB | 3/81 | `█████░░░░░░░░░░ 35%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.37GB | 76/81 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.91GB | 70/81 | `████████░░░░░░░ 53%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/81 | `██████░░░░░░░░░ 42%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.75GB | 75/81 | `█████░░░░░░░░░░ 39%` |
| 5 | `reflect.growslice` | 22.09GB | 31/81 | `█████░░░░░░░░░░ 38%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.55GB | 76/81 | `████░░░░░░░░░░░ 32%` |
| 7 | `jackskj/carta.getUniqueId` | 18.52GB | 21/81 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.42GB | 76/81 | `████░░░░░░░░░░░ 32%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/81 | `████░░░░░░░░░░░ 29%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.14GB | 41/81 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
