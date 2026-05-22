# Overview: prod
*Last updated: 2026-05-22 21:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T21:30 (370 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,597 | avg: 15,806 | max: 84,644 | trend: INCREASING (+6.44/hr))
```
▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 142.5MB | avg: 240.8MB | max: 1896.6MB | trend: stable (+0.20MB/hr))
```
▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,597 | 14,259 | +338 | 15,806 | 84,644 | INCREASING (+6.44/hr) |
| Heap InUse | 142.5MB | 158.9MB | -16.4MB | 240.8MB | 1896.6MB | stable (+0.20MB/hr) |
| Heap Sys | 2902.7MB | 2903.1MB | -0.4MB | 4283.4MB | 6579.6MB | |
| Heap Objects | 587,331 | 776,352 | -189021 | 1,004,484 | 8,100,802 | |

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
| 2026-05-22 | 46 | 15,995 | 231.2MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `internal/evaluation.mergeMetadata` | 3.5MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `experiment/local.(*Client).EvaluateV2` | 2.13MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 26.78GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 16.27GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 16.24GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 12.93GB |
| 5 | `experiment/local.topologicalSort` | 10.76GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 8.3GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 5.24GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 4.95GB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.66GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.14GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/370 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/370 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 368/370 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/370 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.92MB | 368/370 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.99MB | 265/370 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/370 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/370 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/370 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.25MB | 58/370 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 131.19GB | 359/370 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.93GB | 365/370 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.91GB | 365/370 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.73GB | 347/370 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.47GB | 346/370 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.06GB | 315/370 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.57GB | 291/370 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.46GB | 305/370 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/370 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.22GB | 187/370 | `██░░░░░░░░░░░░░ 14%` |

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
