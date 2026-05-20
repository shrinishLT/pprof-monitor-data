# Overview: prod
*Last updated: 2026-05-20 21:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T21:02 (251 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,400 | avg: 15,556 | max: 84,644 | trend: INCREASING (+5.40/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁▁▁▁▁▅▁
```

**Heap InUse** (current: 246.5MB | avg: 232.4MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁▁▂▁▂▅▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,400 | 26,148 | -9748 | 15,556 | 84,644 | INCREASING (+5.40/hr) |
| Heap InUse | 246.5MB | 621.3MB | -374.8MB | 232.4MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 766.1MB | 4940.9MB | -4174.8MB | 4327.7MB | 6579.6MB | |
| Heap Objects | 1,130,094 | 2,846,009 | -1715915 | 991,452 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 43 | 16,346 | 241.9MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.58MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 4 | `runtime.mallocgc` | 9.51MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `bufio.NewReaderSize` | 5.52MB |
| 8 | `bufio.NewWriterSize` | 5.52MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 6.87GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 4.07GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 4.06GB |
| 4 | `experiment/local.topologicalSort` | 2.75GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.16GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 1.3GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 1.13GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 713.58MB |
| 9 | `fmt.Sprintf` | 622.65MB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 541.1MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/251 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/251 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 249/251 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/251 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 23.95MB | 249/251 | `█████░░░░░░░░░░ 38%` |
| 6 | `bytes.growSlice` | 13.01MB | 164/251 | `███░░░░░░░░░░░░ 20%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/251 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/251 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.95MB | 32/251 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/251 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.07GB | 240/251 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.49GB | 246/251 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.44GB | 246/251 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.14GB | 238/251 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.5GB | 228/251 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.38GB | 196/251 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.35GB | 173/251 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/251 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/251 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.54GB | 98/251 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
