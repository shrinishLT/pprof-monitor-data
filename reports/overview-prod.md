# Overview: prod
*Last updated: 2026-05-17 14:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T14:01 (88 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,378 | avg: 15,502 | max: 84,644 | trend: decreasing (-50.87/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 197.2MB | avg: 226.7MB | max: 1896.6MB | trend: decreasing (-3.29MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,378 | 14,399 | +979 | 15,502 | 84,644 | decreasing (-50.87/hr) |
| Heap InUse | 197.2MB | 159.6MB | +37.6MB | 226.7MB | 1896.6MB | decreasing (-3.29MB/hr) |
| Heap Sys | 565.1MB | 2743.1MB | -2178.0MB | 4274.0MB | 5842.7MB | |
| Heap Objects | 934,273 | 655,288 | +278985 | 984,676 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 29 | 15,096 | 189.7MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `bytes.growSlice` | 9.14MB |
| 4 | `runtime.mallocgc` | 8.58MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bufio.NewReaderSize` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 3.01MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 4.13GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 2.51GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 2.42GB |
| 4 | `experiment/local.topologicalSort` | 1.64GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 1.36GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.26GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 784.55MB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 648.64MB |
| 9 | `segmentio/kafka-go.makePartitions` | 478.72MB |
| 10 | `fmt.Sprintf` | 441.94MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 86/88 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/88 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/88 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.44MB | 86/88 | `██████████░░░░░ 69%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/88 | `███████░░░░░░░░ 50%` |
| 6 | `bytes.growSlice` | 14.97MB | 43/88 | `██████░░░░░░░░░ 40%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.39MB | 20/88 | `█████░░░░░░░░░░ 36%` |
| 8 | `database/sql.convertAssignRows` | 13.33MB | 6/88 | `█████░░░░░░░░░░ 36%` |
| 9 | `crypto/tls.Client` | 13.01MB | 3/88 | `█████░░░░░░░░░░ 35%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/88 | `████░░░░░░░░░░░ 32%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.54GB | 81/88 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.69GB | 77/88 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/88 | `██████░░░░░░░░░ 42%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.84GB | 79/88 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 20.37GB | 36/88 | `█████░░░░░░░░░░ 36%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.44GB | 83/88 | `████░░░░░░░░░░░ 32%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.31GB | 83/88 | `████░░░░░░░░░░░ 32%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/88 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/88 | `████░░░░░░░░░░░ 28%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.37GB | 33/88 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
