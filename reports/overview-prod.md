# Overview: prod
*Last updated: 2026-05-17 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T05:31 (71 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,277 | avg: 15,479 | max: 84,644 | trend: decreasing (-102.88/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 157.8MB | avg: 230.1MB | max: 1896.6MB | trend: decreasing (-5.61MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,277 | 14,597 | +680 | 15,479 | 84,644 | decreasing (-102.88/hr) |
| Heap InUse | 157.8MB | 189.9MB | -32.1MB | 230.1MB | 1896.6MB | decreasing (-5.61MB/hr) |
| Heap Sys | 4129.4MB | 3765.6MB | +363.8MB | 4465.2MB | 5842.7MB | |
| Heap Objects | 538,727 | 1,077,698 | -538971 | 1,003,591 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 12 | 14,387 | 157.4MB | 189.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `bytes.growSlice` | 9.55MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `bufio.NewWriterSize` | 5.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `bufio.NewReaderSize` | 3.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.22GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 28.3GB |
| 3 | `internal/evaluation.mergeMetadata` | 22.3GB |
| 4 | `segmentio/kafka-go.makePartitions` | 21.01GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 13.69GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 13.61GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.14GB |
| 8 | `reflect.unsafe_NewArray` | 10.86GB |
| 9 | `reflect.growslice` | 10.09GB |
| 10 | `jackskj/carta.getUniqueId` | 9.78GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 69/71 | `███████████████ 100%` |
| 2 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/71 | `████████████░░░ 83%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/71 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 26.73MB | 69/71 | `██████████░░░░░ 72%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.43MB | 4/71 | `█████████░░░░░░ 63%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 18.13MB | 12/71 | `███████░░░░░░░░ 49%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/71 | `██████░░░░░░░░░ 45%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/71 | `██████░░░░░░░░░ 45%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/71 | `██████░░░░░░░░░ 44%` |
| 10 | `bytes.growSlice` | 16.12MB | 30/71 | `██████░░░░░░░░░ 44%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.97GB | 66/71 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 31.15GB | 60/71 | `████████░░░░░░░ 59%` |
| 3 | `reflect.growslice` | 24.81GB | 24/71 | `███████░░░░░░░░ 47%` |
| 4 | `fmt.(*buffer).writeString` | 24.63GB | 15/71 | `███████░░░░░░░░ 47%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.73GB | 65/71 | `█████░░░░░░░░░░ 37%` |
| 6 | `jackskj/carta.getUniqueId` | 19.07GB | 18/71 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 18.63GB | 66/71 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.(*Client).EvaluateV2` | 18.49GB | 66/71 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.87GB | 28/71 | `████░░░░░░░░░░░ 32%` |
| 10 | `experiment/local.topologicalSort` | 13.03GB | 56/71 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
