# Overview: prod
*Last updated: 2026-05-17 11:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T11:31 (83 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,682 | avg: 15,530 | max: 84,644 | trend: decreasing (-56.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 329.3MB | avg: 229.3MB | max: 1896.6MB | trend: decreasing (-3.51MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,682 | 15,116 | +566 | 15,530 | 84,644 | decreasing (-56.37/hr) |
| Heap InUse | 329.3MB | 254.2MB | +75.1MB | 229.3MB | 1896.6MB | decreasing (-3.51MB/hr) |
| Heap Sys | 5677.1MB | 4095.3MB | +1581.8MB | 4434.0MB | 5842.7MB | |
| Heap Objects | 1,203,530 | 714,332 | +489198 | 997,025 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 24 | 15,107 | 191.1MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 57.81MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 14.08MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 6.02MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 8 | `bufio.NewReaderSize` | 3.03MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 106.39GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.54GB |
| 3 | `internal/evaluation.mergeMetadata` | 46.25GB |
| 4 | `segmentio/kafka-go.makePartitions` | 29.12GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 28.08GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 27.87GB |
| 7 | `jackskj/carta.getUniqueId` | 23.68GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 23.63GB |
| 9 | `reflect.growslice` | 21.84GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 19.87GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 81/83 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/83 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/83 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 26.18MB | 81/83 | `██████████░░░░░ 71%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/83 | `███████░░░░░░░░ 50%` |
| 6 | `bytes.growSlice` | 15.75MB | 38/83 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.16MB | 17/83 | `██████░░░░░░░░░ 41%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/83 | `█████░░░░░░░░░░ 36%` |
| 9 | `database/sql.convertAssignRows` | 13.33MB | 6/83 | `█████░░░░░░░░░░ 36%` |
| 10 | `crypto/tls.Client` | 13.01MB | 3/83 | `█████░░░░░░░░░░ 35%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.51GB | 78/83 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.27GB | 72/83 | `████████░░░░░░░ 53%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/83 | `██████░░░░░░░░░ 41%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 23.37GB | 77/83 | `█████░░░░░░░░░░ 39%` |
| 5 | `reflect.growslice` | 22.04GB | 33/83 | `█████░░░░░░░░░░ 37%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 21.02GB | 2/83 | `█████░░░░░░░░░░ 35%` |
| 7 | `jackskj/carta.getUniqueId` | 18.89GB | 23/83 | `████░░░░░░░░░░░ 32%` |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 18.76GB | 78/83 | `████░░░░░░░░░░░ 32%` |
| 9 | `experiment/local.(*Client).EvaluateV2` | 18.62GB | 78/83 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/83 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
