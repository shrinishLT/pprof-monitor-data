# Overview: prod
*Last updated: 2026-06-07 00:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T00:10 (1820 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,087 | avg: 12,883 | max: 84,644 | trend: INCREASING (+3.41/hr))
```
▂▁▁▃▂▅▁▁▃▂▆▂▂▆▃▅▄▂▃▃▁▁▇▄▄█▂▁▂▂▂▂▂▂▇▃▁▂▅▃▄▁▁▁▂▃▅▂▁▁▆▁▂▁▂▂▂▃▄▁▂▄▃▂▃▂▃▁▁▁▃▁▅▁▁▁▁▁▁▁▁▁▃▁▄▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.2MB | avg: 191.9MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▄▂▂▆▁▃▇▆█▄▂▂▁▂▂▅▃▁▄▄▂▅▅▅▄▃▄▄▄▅▃▂▂▄▅▄▅▁▅▄▇▆▄▄▄▃▆▂▆▁▄▁▂▃▇▂▂▅▅▄▁▄▆▁▆▁▄▃▁▃▇▆▆▄▂▆▃▆▄▁▅▁▇▄▅▄▂▅▅▃▁▆▃▁▆▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,087 | 14,094 | -7 | 12,883 | 84,644 | INCREASING (+3.41/hr) |
| Heap InUse | 161.2MB | 173.0MB | -11.8MB | 191.9MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 853.6MB | 853.7MB | -0.1MB | 2318.7MB | 6883.9MB | |
| Heap Objects | 887,453 | 1,297,639 | -410186 | 861,391 | 17,165,538 | |

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
| 2026-06-07 | 3 | 14,095 | 149.3MB | 173.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 14.95GB |
| 2 | `reflect.unsafe_NewArray` | 7.6GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.12GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.01GB |
| 5 | `reflect.MakeSlice` | 4.25GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.58GB |
| 7 | `reflect.growslice` | 2.2GB |
| 8 | `fmt.Sprintf` | 2.08GB |
| 9 | `jackskj/carta.getUniqueId` | 2.0GB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.9GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 423.71MB | 422.21MB | 380.30MB | 0B |
| `evaluation.mergeMetadata` | 221.55MB | 220.05MB | 198.25MB | 0B |
| `local.(*Client).EvaluateV2` | 638.99MB | 635.96MB | 571.07MB | 0B |
| `local.topologicalSort` | 87.56MB | 86.03MB | 76.63MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 639.09MB | 638.08MB | 569.67MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 62.30MB | 60.28MB | 56.62MB | 0B |
| `localEvaluation.getMapOfValue` | 639.09MB | 638.08MB | 569.67MB | 0B |
| `utils.ParseFeatureFlag` | 640.59MB | 639.58MB | 570.88MB | 0B |

**Total FF alloc (current snapshot):** 3.27GB  |  **24h avg:** 2.92GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1820 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1820 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1471/1820 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 35.4MB | 76/1820 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1820 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.97MB | 1471/1820 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.91MB | 1107/1820 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1820 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1820 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1820 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1820 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1820 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1820 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1820 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1820 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1820 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.93GB | 1234/1820 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1820 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1820 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1820 | `█░░░░░░░░░░░░░░ 10%` |

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
