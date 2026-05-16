# Overview: prod
*Last updated: 2026-05-16 10:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T10:01 (32 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,322 | avg: 16,929 | max: 84,644 | trend: INCREASING (+72.24/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 321.9MB | avg: 300.7MB | max: 1896.6MB | trend: INCREASING (+5.10MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,322 | 14,710 | +612 | 16,929 | 84,644 | INCREASING (+72.24/hr) |
| Heap InUse | 321.9MB | 235.1MB | +86.8MB | 300.7MB | 1896.6MB | INCREASING (+5.10MB/hr) |
| Heap Sys | 5839.3MB | 5837.6MB | +1.7MB | 5069.4MB | 5839.3MB | |
| Heap Objects | 1,539,262 | 728,646 | +810616 | 1,180,236 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 22 | 18,119 | 328.5MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bufio.NewReaderSize` | 6.55MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `bytes.growSlice` | 5.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 3.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 67.18GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 64.55GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 41.05GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 40.63GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 29.33GB |
| 6 | `experiment/local.topologicalSort` | 26.83GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.08GB |
| 8 | `jackskj/carta.getUniqueId` | 17.19GB |
| 9 | `reflect.growslice` | 16.51GB |
| 10 | `fmt.(*buffer).writeString` | 13.46GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 30/32 | `███████████████ 100%` |
| 2 | `runtime.mallocgc` | 34.37MB | 30/32 | `██████████████░ 93%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/32 | `████████████░░░ 83%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/32 | `████████████░░░ 81%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/32 | `███████████░░░░ 78%` |
| 6 | `bytes.growSlice` | 23.91MB | 18/32 | `█████████░░░░░░ 65%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/32 | `██████░░░░░░░░░ 45%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/32 | `██████░░░░░░░░░ 45%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/32 | `██████░░░░░░░░░ 40%` |
| 10 | `reflect.growslice` | 11.07MB | 2/32 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.46GB | 27/32 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 42.27GB | 21/32 | `█████████░░░░░░ 62%` |
| 3 | `fmt.(*buffer).writeString` | 28.95GB | 7/32 | `██████░░░░░░░░░ 42%` |
| 4 | `reflect.growslice` | 25.92GB | 15/32 | `█████░░░░░░░░░░ 38%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 23.28GB | 27/32 | `█████░░░░░░░░░░ 34%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 23.13GB | 27/32 | `█████░░░░░░░░░░ 34%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 21.21GB | 26/32 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 16.91GB | 21/32 | `███░░░░░░░░░░░░ 25%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.93GB | 20/32 | `███░░░░░░░░░░░░ 20%` |
| 10 | `jackskj/carta.getUniqueId` | 13.71GB | 9/32 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.0x avg)
