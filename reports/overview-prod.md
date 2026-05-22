# Overview: prod
*Last updated: 2026-05-22 14:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T14:00 (355 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,241 | avg: 15,816 | max: 84,644 | trend: INCREASING (+7.64/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁
```

**Heap InUse** (current: 159.7MB | avg: 242.4MB | max: 1896.6MB | trend: stable (+0.28MB/hr))
```
▂▁▄▂▁▁▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,241 | 15,962 | -721 | 15,816 | 84,644 | INCREASING (+7.64/hr) |
| Heap InUse | 159.7MB | 240.0MB | -80.3MB | 242.4MB | 1896.6MB | stable (+0.28MB/hr) |
| Heap Sys | 5062.7MB | 5061.8MB | +0.9MB | 4290.6MB | 6579.6MB | |
| Heap Objects | 602,608 | 1,200,477 | -597869 | 1,009,921 | 8,100,802 | |

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
| 2026-05-22 | 31 | 16,198 | 245.1MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 11.56MB |
| 3 | `runtime.mallocgc` | 9.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `internal/evaluation.mergeMetadata` | 4.0MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 3.69MB |
| 8 | `bufio.NewWriterSize` | 3.03MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 65.1GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 39.17GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 38.94GB |
| 4 | `experiment/local.topologicalSort` | 26.02GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.36GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 13.13GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 12.43GB |
| 8 | `fmt.Sprintf` | 5.93GB |
| 9 | `reflect.growslice` | 5.66GB |
| 10 | `jackskj/carta.getUniqueId` | 5.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/355 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/355 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 353/355 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/355 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.56MB | 353/355 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.2MB | 252/355 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/355 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/355 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/355 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 54/355 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 133.75GB | 344/355 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.41GB | 350/355 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.39GB | 350/355 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.86GB | 332/355 | `██████░░░░░░░░░ 41%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 53.99GB | 331/355 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.23GB | 300/355 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.42GB | 276/355 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.4GB | 290/355 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/355 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.86GB | 176/355 | `██░░░░░░░░░░░░░ 14%` |

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
