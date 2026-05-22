# Overview: prod
*Last updated: 2026-05-22 12:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T12:00 (351 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,112 | avg: 15,821 | max: 84,644 | trend: INCREASING (+8.08/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁
```

**Heap InUse** (current: 147.8MB | avg: 243.0MB | max: 1896.6MB | trend: stable (+0.31MB/hr))
```
▂▁▁▂▂▁▄▂▁▁▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,112 | 15,251 | -139 | 15,821 | 84,644 | INCREASING (+8.08/hr) |
| Heap InUse | 147.8MB | 156.5MB | -8.7MB | 243.0MB | 1896.6MB | stable (+0.31MB/hr) |
| Heap Sys | 980.8MB | 986.7MB | -5.9MB | 4305.1MB | 6579.6MB | |
| Heap Objects | 507,037 | 615,509 | -108472 | 1,011,516 | 8,100,802 | |

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
| 2026-05-22 | 27 | 16,319 | 253.0MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 9.55MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `runtime.mallocgc` | 8.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `bufio.NewReaderSize` | 4.52MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `internal/evaluation.mergeMetadata` | 3.0MB |
| 9 | `bufio.NewWriterSize` | 2.52MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 7.8GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 4.79GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 4.6GB |
| 4 | `experiment/local.topologicalSort` | 3.09GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.08GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.46GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 1.46GB |
| 8 | `reflect.growslice` | 1.46GB |
| 9 | `jackskj/carta.getUniqueId` | 1.33GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 1.15GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/351 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/351 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 349/351 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/351 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.75MB | 349/351 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 14.27MB | 248/351 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/351 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/351 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.75MB | 52/351 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/351 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 134.81GB | 340/351 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 80.02GB | 346/351 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 80.0GB | 346/351 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 55.31GB | 328/351 | `██████░░░░░░░░░ 41%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 54.56GB | 327/351 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.68GB | 296/351 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.75GB | 272/351 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.4GB | 290/351 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/351 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `fmt.Sprintf` | 20.13GB | 173/351 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
