# Overview: prod
*Last updated: 2026-05-17 05:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T05:02 (70 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,597 | avg: 15,482 | max: 84,644 | trend: decreasing (-106.85/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 189.9MB | avg: 231.1MB | max: 1896.6MB | trend: decreasing (-5.67MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,597 | 14,069 | +528 | 15,482 | 84,644 | decreasing (-106.85/hr) |
| Heap InUse | 189.9MB | 165.3MB | +24.6MB | 231.1MB | 1896.6MB | decreasing (-5.67MB/hr) |
| Heap Sys | 3765.6MB | 3765.6MB | +0.0MB | 4470.0MB | 5842.7MB | |
| Heap Objects | 1,077,698 | 1,180,841 | -103143 | 1,010,232 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 11 | 14,306 | 157.3MB | 189.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `reflect.growslice` | 5.77MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `fmt.(*buffer).writeString` | 4.76MB |
| 7 | `bytes.growSlice` | 4.02MB |
| 8 | `bufio.NewWriterSize` | 3.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.48GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 26.14GB |
| 3 | `segmentio/kafka-go.makePartitions` | 20.38GB |
| 4 | `internal/evaluation.mergeMetadata` | 20.15GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 12.39GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 12.28GB |
| 7 | `reflect.unsafe_NewArray` | 10.5GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 9.31GB |
| 9 | `database/sql.convertAssignRows` | 8.04GB |
| 10 | `experiment/local.topologicalSort` | 8.03GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 68/70 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/70 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/70 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 26.96MB | 68/70 | `███████████░░░░ 73%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/70 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 19.41MB | 11/70 | `███████░░░░░░░░ 52%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/70 | `██████░░░░░░░░░ 45%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/70 | `██████░░░░░░░░░ 45%` |
| 9 | `bytes.growSlice` | 16.35MB | 29/70 | `██████░░░░░░░░░ 44%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/70 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.81GB | 65/70 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.3GB | 59/70 | `█████████░░░░░░ 60%` |
| 3 | `reflect.growslice` | 25.45GB | 23/70 | `███████░░░░░░░░ 49%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/70 | `███████░░░░░░░░ 47%` |
| 5 | `jackskj/carta.getUniqueId` | 19.62GB | 17/70 | `█████░░░░░░░░░░ 37%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 19.6GB | 64/70 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.71GB | 65/70 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.57GB | 65/70 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/70 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.03GB | 56/70 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
