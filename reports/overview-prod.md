# Overview: prod
*Last updated: 2026-05-22 17:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T17:03 (361 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,518 | avg: 15,812 | max: 84,644 | trend: INCREASING (+7.16/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 303.6MB | avg: 242.2MB | max: 1896.6MB | trend: stable (+0.26MB/hr))
```
▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,518 | 14,500 | +2018 | 15,812 | 84,644 | INCREASING (+7.16/hr) |
| Heap InUse | 303.6MB | 132.4MB | +171.2MB | 242.2MB | 1896.6MB | stable (+0.26MB/hr) |
| Heap Sys | 5049.9MB | 5050.8MB | -0.9MB | 4303.3MB | 6579.6MB | |
| Heap Objects | 1,565,718 | 373,233 | +1192485 | 1,012,411 | 8,100,802 | |

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
| 2026-05-22 | 37 | 16,103 | 243.3MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.58MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 7.54MB |
| 6 | `bufio.NewReaderSize` | 6.02MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 121.63GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 72.87GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 72.79GB |
| 4 | `experiment/local.topologicalSort` | 48.44GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 38.05GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 32.83GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 23.27GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 12.44GB |
| 9 | `fmt.Sprintf` | 11.84GB |
| 10 | `internal/evaluation.coerceString` | 7.93GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/361 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/361 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 359/361 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/361 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.3MB | 359/361 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.1MB | 258/361 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/361 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/361 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/361 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.51MB | 56/361 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 133.14GB | 350/361 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.06GB | 356/361 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.04GB | 356/361 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.58GB | 338/361 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 53.44GB | 337/361 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.9GB | 306/361 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.17GB | 282/361 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.04GB | 296/361 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/361 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.51GB | 182/361 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
