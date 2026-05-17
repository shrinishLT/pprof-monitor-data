# Overview: prod
*Last updated: 2026-05-17 06:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T06:02 (72 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,744 | avg: 15,469 | max: 84,644 | trend: decreasing (-100.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 195.7MB | avg: 229.6MB | max: 1896.6MB | trend: decreasing (-5.46MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,744 | 15,277 | -533 | 15,469 | 84,644 | decreasing (-100.33/hr) |
| Heap InUse | 195.7MB | 157.8MB | +37.9MB | 229.6MB | 1896.6MB | decreasing (-5.46MB/hr) |
| Heap Sys | 4130.1MB | 4129.4MB | +0.7MB | 4460.6MB | 5842.7MB | |
| Heap Objects | 917,258 | 538,727 | +378531 | 1,002,392 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 13 | 14,414 | 160.3MB | 195.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 83.72MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 24.0MB |
| 4 | `runtime.mallocgc` | 11.01MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 7.61MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 8 | `bytes.growSlice` | 3.52MB |
| 9 | `bufio.NewReaderSize` | 3.01MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 74.8GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 34.15GB |
| 3 | `internal/evaluation.mergeMetadata` | 23.54GB |
| 4 | `segmentio/kafka-go.makePartitions` | 21.72GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 14.41GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 14.36GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 13.09GB |
| 8 | `reflect.unsafe_NewArray` | 11.22GB |
| 9 | `reflect.growslice` | 11.04GB |
| 10 | `jackskj/carta.getUniqueId` | 10.67GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 70/72 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/72 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/72 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/72 | `████████████░░░ 81%` |
| 5 | `runtime.mallocgc` | 26.51MB | 70/72 | `██████████░░░░░ 72%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.93MB | 13/72 | `██████░░░░░░░░░ 46%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/72 | `██████░░░░░░░░░ 45%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/72 | `██████░░░░░░░░░ 45%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/72 | `██████░░░░░░░░░ 44%` |
| 10 | `bytes.growSlice` | 15.71MB | 31/72 | `██████░░░░░░░░░ 42%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.31GB | 67/72 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.03GB | 61/72 | `████████░░░░░░░ 59%` |
| 3 | `fmt.(*buffer).writeString` | 24.63GB | 15/72 | `███████░░░░░░░░ 47%` |
| 4 | `reflect.growslice` | 24.26GB | 25/72 | `██████░░░░░░░░░ 46%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.95GB | 66/72 | `█████░░░░░░░░░░ 38%` |
| 6 | `jackskj/carta.getUniqueId` | 18.63GB | 19/72 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.57GB | 67/72 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.43GB | 67/72 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/72 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.03GB | 56/72 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
