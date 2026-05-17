# Overview: prod
*Last updated: 2026-05-17 16:04 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T16:04 (92 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,899 | avg: 15,471 | max: 84,644 | trend: decreasing (-48.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 138.7MB | avg: 224.6MB | max: 1896.6MB | trend: decreasing (-3.15MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,899 | 15,162 | -263 | 15,471 | 84,644 | decreasing (-48.33/hr) |
| Heap InUse | 138.7MB | 172.3MB | -33.6MB | 224.6MB | 1896.6MB | decreasing (-3.15MB/hr) |
| Heap Sys | 2922.9MB | 2922.6MB | +0.3MB | 4211.8MB | 5842.7MB | |
| Heap Objects | 492,093 | 705,949 | -213856 | 978,461 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 33 | 15,060 | 188.3MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `bytes.growSlice` | 8.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.51MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 18.54GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 12.1GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 11.18GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 11.17GB |
| 5 | `experiment/local.topologicalSort` | 7.44GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.54GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 5.45GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 3.51GB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.92GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.95GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 90/92 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/92 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/92 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 24.69MB | 90/92 | `██████████░░░░░ 67%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/92 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/92 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 14.37MB | 46/92 | `█████░░░░░░░░░░ 39%` |
| 8 | `crypto/tls.Client` | 13.01MB | 3/92 | `█████░░░░░░░░░░ 35%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.49MB | 22/92 | `█████░░░░░░░░░░ 34%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/92 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.35GB | 85/92 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.85GB | 81/92 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/92 | `██████░░░░░░░░░ 44%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.96GB | 83/92 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/92 | `█████░░░░░░░░░░ 37%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.97GB | 87/92 | `████░░░░░░░░░░░ 33%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.85GB | 87/92 | `████░░░░░░░░░░░ 32%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/92 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/92 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.15GB | 37/92 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
