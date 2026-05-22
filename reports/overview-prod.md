# Overview: prod
*Last updated: 2026-05-22 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T20:02 (367 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,212 | avg: 15,814 | max: 84,644 | trend: INCREASING (+6.88/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.5MB | avg: 241.4MB | max: 1896.6MB | trend: stable (+0.22MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,212 | 15,386 | +826 | 15,814 | 84,644 | INCREASING (+6.88/hr) |
| Heap InUse | 172.5MB | 194.0MB | -21.5MB | 241.4MB | 1896.6MB | stable (+0.22MB/hr) |
| Heap Sys | 2905.1MB | 2285.2MB | +619.9MB | 4294.7MB | 6579.6MB | |
| Heap Objects | 480,206 | 941,509 | -461303 | 1,007,368 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 43 | 16,080 | 236.2MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.07MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `runtime.mallocgc` | 9.08MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 6 | `bufio.NewReaderSize` | 5.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 8 | `bufio.NewWriterSize` | 4.01MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 10 | `internal/evaluation.mergeMetadata` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 17.56GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 10.64GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 10.64GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 8.35GB |
| 5 | `experiment/local.topologicalSort` | 6.99GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.33GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 3.38GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 3.19GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.9GB |
| 10 | `fmt.Sprintf` | 2.04GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/367 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/367 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 365/367 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/367 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.05MB | 365/367 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.01MB | 264/367 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/367 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/367 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/367 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.37MB | 57/367 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 132.1GB | 356/367 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 78.46GB | 362/367 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 78.44GB | 362/367 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.12GB | 344/367 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.83GB | 343/367 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.43GB | 312/367 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.83GB | 288/367 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.67GB | 302/367 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/367 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.22GB | 187/367 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
