# Overview: prod
*Last updated: 2026-06-07 03:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T03:15 (1857 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,108 | avg: 12,909 | max: 84,644 | trend: INCREASING (+3.38/hr))
```
▁▃▂▃▁▁▁▁▂▃▂▁▁▃▁▁▁▁▁▁▂▃▁▁▃▂▁▂▂▂▁▁▁▂▁▃▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▂▁▁▁█▇▅▁▂▁▁▁▁▁▁▁▁▁▁▃▁
```

**Heap InUse** (current: 123.7MB | avg: 191.2MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▁▃▃▅▄▃▃▃▂▄▂▄▁▃▁▂▂▅▂▂▄▄▃▁▃▄▁▄▁▃▂▁▃▅▄▄▃▂▅▃▄▃▁▃▁▅▃▃▃▂▄▄▂▁▄▂▁▄▄▅▃▂▄▃▂▅▃▁▁▅▄▄▆▃▄▃▄▅▁▆█▃▅▂▁▃▁▁▁▃▄▄▄▄▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,108 | 14,410 | -302 | 12,909 | 84,644 | INCREASING (+3.38/hr) |
| Heap InUse | 123.7MB | 175.4MB | -51.7MB | 191.2MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 854.2MB | 853.4MB | +0.8MB | 2289.5MB | 6883.9MB | |
| Heap Objects | 567,265 | 1,054,685 | -487420 | 862,162 | 17,165,538 | |

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
| 2026-06-07 | 40 | 14,224 | 154.9MB | 233.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `reflect.unsafe_NewArray` | 2.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.01MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 19.18GB |
| 2 | `reflect.unsafe_NewArray` | 9.82GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 8.05GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 6.59GB |
| 5 | `reflect.MakeSlice` | 5.51GB |
| 6 | `reflect.growslice` | 4.58GB |
| 7 | `jackskj/carta.getUniqueId` | 4.11GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 4.01GB |
| 9 | `reflect.unsafe_New` | 3.82GB |
| 10 | `fmt.Sprintf` | 3.28GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 492.75MB | 490.70MB | 446.17MB | 0B |
| `evaluation.mergeMetadata` | 256.06MB | 255.56MB | 233.04MB | 0B |
| `local.(*Client).EvaluateV2` | 751.57MB | 747.49MB | 677.50MB | 0B |
| `local.topologicalSort` | 102.26MB | 101.76MB | 92.98MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 754.74MB | 749.62MB | 679.97MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 70.49MB | 70.49MB | 64.48MB | 0B |
| `localEvaluation.getMapOfValue` | 754.74MB | 749.62MB | 679.97MB | 0B |
| `utils.ParseFeatureFlag` | 756.74MB | 751.62MB | 681.80MB | 0B |

**Total FF alloc (current snapshot):** 3.85GB  |  **24h avg:** 3.47GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1857 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1857 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1508/1857 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 34.98MB | 77/1857 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1857 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.84MB | 1508/1857 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.83MB | 1115/1857 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1857 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1857 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1857 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1857 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1857 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1857 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1857 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1857 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1857 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.23GB | 1271/1857 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1857 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1857 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1857 | `█░░░░░░░░░░░░░░ 10%` |

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
