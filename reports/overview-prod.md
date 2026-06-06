# Overview: prod
*Last updated: 2026-06-07 02:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T02:40 (1850 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,109 | avg: 12,905 | max: 84,644 | trend: INCREASING (+3.39/hr))
```
▁▂▂▁▄▂▁▁▃▂▃▁▁▁▁▂▃▂▁▁▃▁▁▁▁▁▁▂▃▁▁▃▂▁▂▂▂▁▁▁▂▁▃▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▂▁▁▁█▇▅▁▂▁▁▁▁▁
```

**Heap InUse** (current: 119.0MB | avg: 191.3MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▂▂▂▃▄▃▄▁▃▃▅▄▃▃▃▂▄▂▄▁▃▁▂▂▅▂▂▄▄▃▁▃▄▁▄▁▃▂▁▃▅▄▄▃▂▅▃▄▃▁▃▁▅▃▃▃▂▄▄▂▁▄▂▁▄▄▅▃▂▄▃▂▅▃▁▁▅▄▄▆▃▄▃▄▅▁▆█▃▅▂▁▃▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,109 | 14,091 | +18 | 12,905 | 84,644 | INCREASING (+3.39/hr) |
| Heap InUse | 119.0MB | 102.9MB | +16.1MB | 191.3MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 854.2MB | 855.2MB | -1.0MB | 2294.9MB | 6883.9MB | |
| Heap Objects | 711,239 | 332,229 | +379010 | 861,641 | 17,165,538 | |

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
| 2026-06-07 | 33 | 14,237 | 154.0MB | 233.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.04MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 18.36GB |
| 2 | `reflect.unsafe_NewArray` | 9.41GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.59GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 6.21GB |
| 5 | `reflect.MakeSlice` | 5.28GB |
| 6 | `reflect.growslice` | 4.56GB |
| 7 | `jackskj/carta.getUniqueId` | 4.1GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 3.92GB |
| 9 | `reflect.unsafe_New` | 3.81GB |
| 10 | `fmt.Sprintf` | 3.23GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 477.51MB | 473.50MB | 434.12MB | 0B |
| `evaluation.mergeMetadata` | 248.56MB | 245.56MB | 227.01MB | 0B |
| `local.(*Client).EvaluateV2` | 727.59MB | 723.58MB | 657.80MB | 0B |
| `local.topologicalSort` | 99.73MB | 99.73MB | 90.05MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 730.75MB | 725.71MB | 659.60MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 68.96MB | 68.96MB | 62.97MB | 0B |
| `localEvaluation.getMapOfValue` | 730.75MB | 725.71MB | 659.60MB | 0B |
| `utils.ParseFeatureFlag` | 732.75MB | 727.71MB | 661.35MB | 0B |

**Total FF alloc (current snapshot):** 3.73GB  |  **24h avg:** 3.37GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1850 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1850 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1501/1850 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 34.98MB | 77/1850 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1850 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.86MB | 1501/1850 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.85MB | 1114/1850 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1850 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1850 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1850 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1850 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1850 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1850 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1850 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1850 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1850 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.36GB | 1264/1850 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1850 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1850 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1850 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
