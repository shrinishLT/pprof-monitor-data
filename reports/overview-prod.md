# Overview: prod
*Last updated: 2026-06-07 01:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T01:35 (1837 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,386 | avg: 12,894 | max: 84,644 | trend: INCREASING (+3.39/hr))
```
▂▃▃▁▁▇▄▃▇▂▁▂▂▂▂▂▂▇▃▁▂▅▃▄▁▁▁▂▂▅▂▁▁▅▁▁▁▂▂▂▃▄▁▂▄▃▂▃▂▃▁▁▁▃▁▅▁▁▁▁▁▁▁▁▁▃▁▄▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▄
```

**Heap InUse** (current: 142.9MB | avg: 191.6MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▁▄▃▂▅▅▅▃▃▄▃▃▄▃▂▂▄▅▄▄▁▄▄▆▅▄▄▄▃▅▂▅▁▄▁▂▂▆▂▂▄▄▄▁▃▅▁▅▁▄▃▁▃▆▅▅▄▂▅▃▅▄▁▄▁▆▄▄▄▂▅▅▃▁▅▃▁▅▄▆▄▂▅▄▂▆▄▁▁▆▅▄█▃▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,386 | 14,081 | +305 | 12,894 | 84,644 | INCREASING (+3.39/hr) |
| Heap InUse | 142.9MB | 173.3MB | -30.4MB | 191.6MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 853.3MB | 853.8MB | -0.5MB | 2305.1MB | 6883.9MB | |
| Heap Objects | 679,537 | 1,305,666 | -626129 | 862,350 | 17,165,538 | |

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
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 20 | 14,153 | 155.7MB | 207.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.92GB |
| 2 | `reflect.unsafe_NewArray` | 8.65GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.14GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.83GB |
| 5 | `reflect.MakeSlice` | 4.84GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.8GB |
| 7 | `reflect.growslice` | 2.27GB |
| 8 | `fmt.Sprintf` | 2.17GB |
| 9 | `segmentio/kafka-go.makeLayout` | 2.14GB |
| 10 | `jackskj/carta.getUniqueId` | 2.03GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 448.57MB | 446.02MB | 412.13MB | 0B |
| `evaluation.mergeMetadata` | 234.56MB | 233.56MB | 215.81MB | 0B |
| `local.(*Client).EvaluateV2` | 684.11MB | 677.97MB | 621.39MB | 0B |
| `local.topologicalSort` | 94.65MB | 94.15MB | 84.51MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 686.74MB | 680.08MB | 622.28MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 65.40MB | 65.40MB | 60.22MB | 0B |
| `localEvaluation.getMapOfValue` | 686.74MB | 680.08MB | 622.28MB | 0B |
| `utils.ParseFeatureFlag` | 688.74MB | 682.08MB | 623.79MB | 0B |

**Total FF alloc (current snapshot):** 3.51GB  |  **24h avg:** 3.19GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1837 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1837 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1488/1837 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 34.98MB | 77/1837 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1837 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.91MB | 1488/1837 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.88MB | 1110/1837 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1837 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1837 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1837 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1837 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1837 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1837 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1837 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1837 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1837 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.6GB | 1251/1837 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1837 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1837 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1837 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
