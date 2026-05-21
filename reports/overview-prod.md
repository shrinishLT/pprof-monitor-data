# Overview: prod
*Last updated: 2026-05-21 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T10:30 (284 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,845 | avg: 15,706 | max: 84,644 | trend: INCREASING (+8.84/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁
```

**Heap InUse** (current: 406.6MB | avg: 235.9MB | max: 1896.6MB | trend: stable (+0.23MB/hr))
```
▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,845 | 22,203 | -4358 | 15,706 | 84,644 | INCREASING (+8.84/hr) |
| Heap InUse | 406.6MB | 286.4MB | +120.2MB | 235.9MB | 1896.6MB | stable (+0.23MB/hr) |
| Heap Sys | 2798.5MB | 3754.1MB | -955.6MB | 4214.0MB | 6579.6MB | |
| Heap Objects | 1,533,432 | 669,086 | +864346 | 996,207 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 28 | 15,748 | 239.5MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 53.29MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 35.36MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 27.63MB |
| 5 | `bufio.NewReaderSize` | 25.1MB |
| 6 | `bufio.NewWriterSize` | 21.6MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 10 | `crypto/tls.Client` | 6.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 7.6GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 4.49GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 4.48GB |
| 4 | `experiment/local.topologicalSort` | 3.01GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.45GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 1.46GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 1.37GB |
| 8 | `reflect.growslice` | 822.46MB |
| 9 | `jackskj/carta.getUniqueId` | 756.62MB |
| 10 | `reflect.unsafe_New` | 688.81MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/284 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/284 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 282/284 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/284 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.66MB | 282/284 | `██████░░░░░░░░░ 40%` |
| 6 | `bytes.growSlice` | 13.9MB | 193/284 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/284 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/284 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.87MB | 42/284 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/284 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 115.86GB | 273/284 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.73GB | 279/284 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.7GB | 279/284 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 57.09GB | 261/284 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 47.93GB | 261/284 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.21GB | 229/284 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.61GB | 205/284 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.05GB | 237/284 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/284 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.98GB | 114/284 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
