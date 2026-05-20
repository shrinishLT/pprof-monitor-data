# Overview: prod
*Last updated: 2026-05-20 21:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T21:30 (252 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,265 | avg: 15,575 | max: 84,644 | trend: INCREASING (+6.22/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁▁▁▁▁▅▁▃
```

**Heap InUse** (current: 309.9MB | avg: 232.7MB | max: 1896.6MB | trend: stable (+0.19MB/hr))
```
▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁▁▂▁▂▅▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,265 | 16,400 | +3865 | 15,575 | 84,644 | INCREASING (+6.22/hr) |
| Heap InUse | 309.9MB | 246.5MB | +63.4MB | 232.7MB | 1896.6MB | stable (+0.19MB/hr) |
| Heap Sys | 742.2MB | 766.1MB | -23.9MB | 4313.5MB | 6579.6MB | |
| Heap Objects | 1,041,543 | 1,130,094 | -88551 | 991,651 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 44 | 16,435 | 243.5MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 26.13MB |
| 3 | `bufio.NewWriterSize` | 17.57MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.57MB |
| 5 | `runtime.mallocgc` | 13.1MB |
| 6 | `bufio.NewReaderSize` | 11.06MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.5MB |
| 10 | `crypto/tls.Client` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 21.03GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 12.56GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 12.49GB |
| 4 | `experiment/local.topologicalSort` | 8.34GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.58GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 4.01GB |
| 7 | `fmt.Sprintf` | 1.99GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 1.83GB |
| 9 | `jackskj/carta.getUniqueId` | 1.57GB |
| 10 | `reflect.growslice` | 1.46GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/252 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/252 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 250/252 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/252 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 23.91MB | 250/252 | `█████░░░░░░░░░░ 38%` |
| 6 | `bytes.growSlice` | 13.09MB | 165/252 | `███░░░░░░░░░░░░ 21%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/252 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/252 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.95MB | 32/252 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/252 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.67GB | 241/252 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.26GB | 247/252 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.2GB | 247/252 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.14GB | 238/252 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.32GB | 229/252 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.19GB | 197/252 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.2GB | 174/252 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/252 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/252 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.37GB | 99/252 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
