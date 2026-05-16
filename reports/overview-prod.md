# Overview: prod
*Last updated: 2026-05-16 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T05:31 (24 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,127 | avg: 17,716 | max: 84,644 | trend: INCREASING (+694.05/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁
```

**Heap InUse** (current: 324.5MB | avg: 306.1MB | max: 1896.6MB | trend: INCREASING (+17.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,127 | 14,949 | +1178 | 17,716 | 84,644 | INCREASING (+694.05/hr) |
| Heap InUse | 324.5MB | 296.9MB | +27.6MB | 306.1MB | 1896.6MB | INCREASING (+17.02MB/hr) |
| Heap Sys | 5831.0MB | 5829.6MB | +1.4MB | 4814.3MB | 5831.0MB | |
| Heap Objects | 1,049,634 | 1,430,559 | -380925 | 1,194,274 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 14 | 20,148 | 353.8MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `reflect.growslice` | 19.28MB |
| 4 | `bytes.growSlice` | 13.57MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `bufio.NewReaderSize` | 4.53MB |
| 9 | `reflect.unsafe_New` | 4.5MB |
| 10 | `fmt.(*buffer).writeString` | 4.37MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 54.2GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 33.01GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 32.74GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 24.06GB |
| 5 | `experiment/local.topologicalSort` | 21.65GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.08GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 10.91GB |
| 8 | `reflect.growslice` | 10.71GB |
| 9 | `jackskj/carta.getUniqueId` | 10.62GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 10.31GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 38.68MB | 5/24 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 22/24 | `██████████████░ 94%` |
| 3 | `bytes.growSlice` | 31.56MB | 13/24 | `████████████░░░ 81%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/24 | `███████████░░░░ 78%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/24 | `███████████░░░░ 77%` |
| 6 | `runtime.mallocgc` | 25.01MB | 22/24 | `█████████░░░░░░ 64%` |
| 7 | `reflect.growslice` | 19.28MB | 1/24 | `███████░░░░░░░░ 49%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/24 | `██████░░░░░░░░░ 42%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/24 | `██████░░░░░░░░░ 42%` |
| 10 | `bufio.NewReaderSize` | 13.29MB | 12/24 | `█████░░░░░░░░░░ 34%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.55GB | 19/24 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 39.34GB | 7/24 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/24 | `██████░░░░░░░░░ 44%` |
| 4 | `internal/evaluation.mergeMetadata` | 30.41GB | 13/24 | `██████░░░░░░░░░ 42%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 18.97GB | 18/24 | `███░░░░░░░░░░░░ 26%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 17.28GB | 19/24 | `███░░░░░░░░░░░░ 24%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.19GB | 19/24 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 12.2GB | 13/24 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `jackskj/carta.getUniqueId` | 10.62GB | 1/24 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.34GB | 12/24 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.8x avg)
