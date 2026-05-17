# Overview: prod
*Last updated: 2026-05-17 12:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T12:03 (84 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,214 | avg: 15,526 | max: 84,644 | trend: decreasing (-54.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 202.7MB | avg: 229.0MB | max: 1896.6MB | trend: decreasing (-3.43MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,214 | 15,682 | -468 | 15,526 | 84,644 | decreasing (-54.91/hr) |
| Heap InUse | 202.7MB | 329.3MB | -126.6MB | 229.0MB | 1896.6MB | decreasing (-3.43MB/hr) |
| Heap Sys | 293.5MB | 5677.1MB | -5383.6MB | 4384.7MB | 5842.7MB | |
| Heap Objects | 1,012,285 | 1,203,530 | -191245 | 997,207 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 25 | 15,111 | 191.6MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 12.56MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `runtime.mallocgc` | 9.01MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.52MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 9 | `bufio.NewReaderSize` | 3.01MB |
| 10 | `bufio.NewWriterSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 3.99GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 2.44GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 2.38GB |
| 4 | `experiment/local.topologicalSort` | 1.61GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.26GB |
| 6 | `reflect.growslice` | 1.12GB |
| 7 | `jackskj/carta.getUniqueId` | 865.14MB |
| 8 | `reflect.unsafe_New` | 782.35MB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 778.05MB |
| 10 | `carta/value.NewCell` | 564.04MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 82/84 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/84 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/84 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.97MB | 82/84 | `██████████░░░░░ 70%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/84 | `███████░░░░░░░░ 50%` |
| 6 | `bytes.growSlice` | 15.67MB | 39/84 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.54MB | 18/84 | `█████░░░░░░░░░░ 39%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/84 | `█████░░░░░░░░░░ 36%` |
| 9 | `database/sql.convertAssignRows` | 13.33MB | 6/84 | `█████░░░░░░░░░░ 36%` |
| 10 | `crypto/tls.Client` | 13.01MB | 3/84 | `█████░░░░░░░░░░ 35%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.51GB | 78/84 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.9GB | 73/84 | `███████░░░░░░░░ 52%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/84 | `██████░░░░░░░░░ 41%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 23.37GB | 77/84 | `█████░░░░░░░░░░ 39%` |
| 5 | `reflect.growslice` | 21.42GB | 34/84 | `█████░░░░░░░░░░ 36%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 21.02GB | 2/84 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.55GB | 79/84 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.42GB | 79/84 | `████░░░░░░░░░░░ 31%` |
| 9 | `jackskj/carta.getUniqueId` | 18.14GB | 24/84 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.33GB | 29/84 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
