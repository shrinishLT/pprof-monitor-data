# Overview: prod
*Last updated: 2026-05-16 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T10:31 (33 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,211 | avg: 16,847 | max: 84,644 | trend: INCREASING (+36.79/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 211.4MB | avg: 298.0MB | max: 1896.6MB | trend: INCREASING (+3.69MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,211 | 15,322 | -1111 | 16,847 | 84,644 | INCREASING (+36.79/hr) |
| Heap InUse | 211.4MB | 321.9MB | -110.5MB | 298.0MB | 1896.6MB | INCREASING (+3.69MB/hr) |
| Heap Sys | 5842.7MB | 5839.3MB | +3.4MB | 5092.9MB | 5842.7MB | |
| Heap Objects | 657,402 | 1,539,262 | -881860 | 1,164,393 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 23 | 17,949 | 323.4MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 2.14MB |
| 10 | `bufio.NewReaderSize` | 2.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 69.54GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 64.58GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 42.41GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 42.04GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.34GB |
| 6 | `experiment/local.topologicalSort` | 27.75GB |
| 7 | `jackskj/carta.getUniqueId` | 22.81GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.82GB |
| 9 | `reflect.growslice` | 21.69GB |
| 10 | `fmt.(*buffer).writeString` | 18.24GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 31/33 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 35.21MB | 31/33 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/33 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/33 | `████████████░░░ 81%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/33 | `███████████░░░░ 78%` |
| 6 | `bytes.growSlice` | 23.91MB | 18/33 | `█████████░░░░░░ 65%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/33 | `██████░░░░░░░░░ 45%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/33 | `██████░░░░░░░░░ 45%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/33 | `██████░░░░░░░░░ 40%` |
| 10 | `reflect.growslice` | 11.07MB | 2/33 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.36GB | 28/33 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 43.51GB | 22/33 | `█████████░░░░░░ 64%` |
| 3 | `fmt.(*buffer).writeString` | 27.61GB | 8/33 | `██████░░░░░░░░░ 40%` |
| 4 | `reflect.growslice` | 25.65GB | 16/33 | `█████░░░░░░░░░░ 38%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 23.97GB | 28/33 | `█████░░░░░░░░░░ 35%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 23.8GB | 28/33 | `█████░░░░░░░░░░ 35%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.51GB | 27/33 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 17.4GB | 22/33 | `███░░░░░░░░░░░░ 25%` |
| 9 | `jackskj/carta.getUniqueId` | 14.62GB | 10/33 | `███░░░░░░░░░░░░ 21%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.31GB | 21/33 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.0x avg)
