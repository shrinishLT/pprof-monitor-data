# Overview: prod
*Last updated: 2026-05-17 06:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T06:33 (73 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,380 | avg: 15,468 | max: 84,644 | trend: decreasing (-96.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 211.2MB | avg: 229.3MB | max: 1896.6MB | trend: decreasing (-5.28MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,380 | 14,744 | +636 | 15,468 | 84,644 | decreasing (-96.46/hr) |
| Heap InUse | 211.2MB | 195.7MB | +15.5MB | 229.3MB | 1896.6MB | decreasing (-5.28MB/hr) |
| Heap Sys | 4129.9MB | 4130.1MB | -0.2MB | 4456.1MB | 5842.7MB | |
| Heap Objects | 1,066,063 | 917,258 | +148805 | 1,003,264 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 14 | 14,483 | 163.9MB | 211.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `bytes.growSlice` | 4.52MB |
| 6 | `bufio.NewWriterSize` | 4.52MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `bufio.NewReaderSize` | 3.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 89.49GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 40.77GB |
| 3 | `internal/evaluation.mergeMetadata` | 26.2GB |
| 4 | `segmentio/kafka-go.makePartitions` | 22.4GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 16.01GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 15.97GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 15.18GB |
| 8 | `database/sql.convertAssignRows` | 12.31GB |
| 9 | `reflect.unsafe_NewArray` | 11.58GB |
| 10 | `reflect.growslice` | 11.06GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 71/73 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/73 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/73 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/73 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 26.29MB | 71/73 | `██████████░░░░░ 71%` |
| 6 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/73 | `██████░░░░░░░░░ 45%` |
| 7 | `crypto/tls.Client` | 16.51MB | 2/73 | `██████░░░░░░░░░ 45%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/73 | `██████░░░░░░░░░ 44%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.93MB | 14/73 | `██████░░░░░░░░░ 43%` |
| 10 | `bytes.growSlice` | 15.36MB | 32/73 | `██████░░░░░░░░░ 41%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.86GB | 68/73 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.95GB | 62/73 | `████████░░░░░░░ 58%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/73 | `██████░░░░░░░░░ 46%` |
| 4 | `reflect.growslice` | 23.75GB | 26/73 | `██████░░░░░░░░░ 44%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.26GB | 67/73 | `█████░░░░░░░░░░ 38%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/73 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.53GB | 68/73 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.39GB | 68/73 | `█████░░░░░░░░░░ 34%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/73 | `████░░░░░░░░░░░ 31%` |
| 10 | `experiment/local.topologicalSort` | 13.03GB | 56/73 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
