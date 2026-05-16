# Overview: prod
*Last updated: 2026-05-16 06:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T06:02 (25 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,043 | avg: 17,609 | max: 84,644 | trend: INCREASING (+564.62/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 478.7MB | avg: 313.0MB | max: 1896.6MB | trend: INCREASING (+18.24MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,043 | 16,127 | -1084 | 17,609 | 84,644 | INCREASING (+564.62/hr) |
| Heap InUse | 478.7MB | 324.5MB | +154.2MB | 313.0MB | 1896.6MB | INCREASING (+18.24MB/hr) |
| Heap Sys | 5831.9MB | 5831.0MB | +0.9MB | 4855.0MB | 5831.9MB | |
| Heap Objects | 1,602,599 | 1,049,634 | +552965 | 1,210,607 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 15 | 19,808 | 362.1MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `database/sql.convertAssignRows` | 8.0MB |
| 6 | `bytes.growSlice` | 7.55MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `bufio.NewReaderSize` | 3.03MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `bufio.NewWriterSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 56.51GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 36.83GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 34.42GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 34.12GB |
| 5 | `experiment/local.topologicalSort` | 22.55GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.81GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 16.77GB |
| 8 | `reflect.growslice` | 13.52GB |
| 9 | `jackskj/carta.getUniqueId` | 13.21GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 10.75GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 38.68MB | 5/25 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 23/25 | `██████████████░ 94%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/25 | `███████████░░░░ 78%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/25 | `███████████░░░░ 77%` |
| 5 | `bytes.growSlice` | 29.84MB | 14/25 | `███████████░░░░ 77%` |
| 6 | `runtime.mallocgc` | 26.54MB | 23/25 | `██████████░░░░░ 68%` |
| 7 | `reflect.growslice` | 19.28MB | 1/25 | `███████░░░░░░░░ 49%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/25 | `██████░░░░░░░░░ 42%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/25 | `██████░░░░░░░░░ 42%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.01MB | 1/25 | `█████░░░░░░░░░░ 38%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.82GB | 20/25 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 36.11GB | 8/25 | `███████░░░░░░░░ 51%` |
| 3 | `internal/evaluation.mergeMetadata` | 32.28GB | 14/25 | `██████░░░░░░░░░ 46%` |
| 4 | `fmt.(*buffer).writeString` | 31.53GB | 6/25 | `██████░░░░░░░░░ 45%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 18.86GB | 19/25 | `████░░░░░░░░░░░ 27%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.13GB | 20/25 | `███░░░░░░░░░░░░ 25%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.04GB | 20/25 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 12.94GB | 14/25 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `jackskj/carta.getUniqueId` | 11.91GB | 2/25 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.92GB | 13/25 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.8x avg)
