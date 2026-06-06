# Overview: prod
*Last updated: 2026-06-06 21:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T21:25 (1787 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,271 | avg: 12,859 | max: 84,644 | trend: INCREASING (+3.44/hr))
```
▁▁▁▁▁▁▃▅▄▃▄▄▂█▂▁▅▂▁▂▂▃▁▁▂▁▁▁▁▁▁▂▁▁▁▁▂▁▂▁▁▁▁▂▁▁▃▁▂▂▁▁▁▁▁▃▂▂▃▁▁▁▁▁▁▁▁▃▂▁▁▂▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▁▂▂▁▁▂▁
```

**Heap InUse** (current: 170.2MB | avg: 192.7MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
█▁▂▁▁▁▁▂▂▃▄▂▃▃▂▂▃▂▂▁▃▂▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▁▁▁▁▁▁▂▁▁▂▁▁▂▂▂▁▁▂▁▁▂▁▁▁▂▂▂▂▁▂▂▃▂▂▂▂▁▂▁▂▁▂▁▁▁▂▁▁▂▂▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,271 | 14,431 | -160 | 12,859 | 84,644 | INCREASING (+3.44/hr) |
| Heap InUse | 170.2MB | 148.7MB | +21.5MB | 192.7MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 853.3MB | 853.2MB | +0.1MB | 2345.7MB | 6883.9MB | |
| Heap Objects | 1,084,500 | 669,035 | +415465 | 860,616 | 17,165,538 | |

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
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 258 | 16,037 | 230.1MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 10.03MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.02MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.01MB |
| 10 | `bytes.growSlice` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 11.15GB |
| 2 | `reflect.unsafe_NewArray` | 5.67GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 4.91GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.02GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.29GB |
| 6 | `reflect.MakeSlice` | 3.18GB |
| 7 | `reflect.growslice` | 2.11GB |
| 8 | `jackskj/carta.getUniqueId` | 1.97GB |
| 9 | `fmt.Sprintf` | 1.89GB |
| 10 | `reflect.unsafe_New` | 1.72GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 361.74MB | 358.17MB | 299.56MB | 0B |
| `evaluation.mergeMetadata` | 187.55MB | 186.05MB | 155.91MB | 0B |
| `local.(*Client).EvaluateV2` | 542.91MB | 538.28MB | 446.26MB | 0B |
| `local.topologicalSort` | 72.89MB | 72.89MB | 58.25MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 540.41MB | 535.81MB | 440.67MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 54.66MB | 54.12MB | 46.56MB | 0B |
| `localEvaluation.getMapOfValue` | 540.41MB | 535.81MB | 440.67MB | 0B |
| `utils.ParseFeatureFlag` | 541.41MB | 536.81MB | 441.33MB | 0B |

**Total FF alloc (current snapshot):** 2.78GB  |  **24h avg:** 2.27GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1787 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1787 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1438/1787 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 35.84MB | 75/1787 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1787 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 17.1MB | 1438/1787 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.0MB | 1098/1787 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1787 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1787 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1787 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1787 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1787 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1787 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1787 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1787 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 28.61GB | 1201/1787 | `███░░░░░░░░░░░░ 22%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1787 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1787 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1787 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1787 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
