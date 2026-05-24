# Overview: prod
*Last updated: 2026-05-24 16:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T16:31 (456 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,072 | avg: 15,654 | max: 84,644 | trend: stable (+0.01/hr))
```
▂▁▂▂▁▁▂▁▁▁▂▃▁▅▄▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 145.7MB | avg: 231.9MB | max: 1896.6MB | trend: stable (-0.08MB/hr))
```
▃▁▂▂▁▂▁▁▁▁▃▃▁▃▃▂▁▂▂▂▁▁▁▁▁▁▄▁▁▁▁▁▁▂▃▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,072 | 14,358 | -286 | 15,654 | 84,644 | stable (+0.01/hr) |
| Heap InUse | 145.7MB | 128.8MB | +16.9MB | 231.9MB | 1896.6MB | stable (-0.08MB/hr) |
| Heap Sys | 3534.0MB | 3533.6MB | +0.4MB | 4182.7MB | 6883.9MB | |
| Heap Objects | 940,086 | 466,984 | +473102 | 989,899 | 8,100,802 | |

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
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 34 | 14,919 | 211.5MB | 689.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 19.99GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 7.67GB |
| 3 | `segmentio/kafka-go.makePartitions` | 4.17GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.82GB |
| 5 | `reflect.growslice` | 2.4GB |
| 6 | `database/sql.convertAssignRows` | 2.29GB |
| 7 | `reflect.unsafe_NewArray` | 2.18GB |
| 8 | `jackskj/carta.getUniqueId` | 2.09GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.86GB |
| 10 | `reflect.unsafe_New` | 1.85GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.69MB | 11/456 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.2MB | 18/456 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 454/456 | `██████████░░░░░ 69%` |
| 4 | `database/sql.convertAssignRows` | 30.41MB | 22/456 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 22.4MB | 454/456 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.57MB | 307/456 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/456 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/456 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/456 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/456 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/456 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/456 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/456 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.05GB | 431/456 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/456 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/456 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/456 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.2GB | 388/456 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/456 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 16.3GB | 262/456 | `█░░░░░░░░░░░░░░ 13%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
