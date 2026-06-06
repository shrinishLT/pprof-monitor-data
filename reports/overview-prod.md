# Overview: prod
*Last updated: 2026-06-07 00:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T00:15 (1821 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,417 | avg: 12,883 | max: 84,644 | trend: INCREASING (+3.41/hr))
```
▁▁▃▂▅▁▁▃▂▆▂▂▆▃▅▄▂▃▃▁▁▇▄▄█▂▁▂▂▂▂▂▂▇▃▁▂▅▃▄▁▁▁▂▃▅▂▁▁▆▁▂▁▂▂▂▃▄▁▂▄▃▂▃▂▃▁▁▁▃▁▅▁▁▁▁▁▁▁▁▁▃▁▄▁▁▁▁▁▁▁▁▁▁▁▄
```

**Heap InUse** (current: 189.8MB | avg: 191.9MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▂▂▆▁▃▇▆█▄▂▂▁▂▂▅▃▁▄▄▂▅▅▅▄▃▄▄▄▅▃▂▂▄▅▄▅▁▅▄▇▆▄▄▄▃▆▂▆▁▄▁▂▃▇▂▂▅▅▄▁▄▆▁▆▁▄▃▁▃▇▆▆▄▂▆▃▆▄▁▅▁▇▄▅▄▂▅▅▃▁▆▃▁▆▅▇
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,417 | 14,087 | +330 | 12,883 | 84,644 | INCREASING (+3.41/hr) |
| Heap InUse | 189.8MB | 161.2MB | +28.6MB | 191.9MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 852.9MB | 853.6MB | -0.7MB | 2317.9MB | 6883.9MB | |
| Heap Objects | 1,025,114 | 887,453 | +137661 | 861,481 | 17,165,538 | |

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
| 2026-06-07 | 4 | 14,176 | 159.4MB | 189.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.49MB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.91MB |
| 7 | `database/sql.convertAssignRows` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 15.09GB |
| 2 | `reflect.unsafe_NewArray` | 7.69GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.24GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.1GB |
| 5 | `reflect.MakeSlice` | 4.29GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.67GB |
| 7 | `reflect.growslice` | 2.21GB |
| 8 | `fmt.Sprintf` | 2.08GB |
| 9 | `jackskj/carta.getUniqueId` | 2.0GB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.92GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 426.21MB | 423.71MB | 382.39MB | 0B |
| `evaluation.mergeMetadata` | 223.05MB | 221.55MB | 199.37MB | 0B |
| `local.(*Client).EvaluateV2` | 644.12MB | 638.99MB | 574.30MB | 0B |
| `local.topologicalSort` | 88.56MB | 87.56MB | 77.11MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 644.72MB | 639.09MB | 573.04MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 62.30MB | 62.30MB | 56.86MB | 0B |
| `localEvaluation.getMapOfValue` | 644.72MB | 639.09MB | 573.04MB | 0B |
| `utils.ParseFeatureFlag` | 646.23MB | 640.59MB | 574.26MB | 0B |

**Total FF alloc (current snapshot):** 3.30GB  |  **24h avg:** 2.94GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1821 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1821 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1472/1821 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 34.98MB | 77/1821 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1821 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.97MB | 1472/1821 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.91MB | 1107/1821 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1821 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1821 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1821 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1821 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1821 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1821 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1821 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1821 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1821 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.91GB | 1235/1821 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1821 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1821 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1821 | `█░░░░░░░░░░░░░░ 10%` |

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
