# Overview: prod
*Last updated: 2026-06-05 19:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T19:46 (1480 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,556 | avg: 12,226 | max: 84,644 | trend: stable (-0.05/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▃▃▂▂▄▃▃▃▂▂▂▂▂▂▃▂▂▁▂▂▁▂▂▂▂▃▃▃▂▂▁▂▁▁▂▁▂▂▁▂▆▅▅▄▆█▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▂▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 188.6MB | avg: 185.7MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▁▂▁▁▂▁▁▃▁▂▃▅▅▃▃▆▅▄▄▄▃▃▄▄▅▄▄▄▂▂▄▁▂▄▅▃▅▃▃▃▄▁▄▂▃▁▂▃▃▁▂▆▇▇▅▇█▇▆▂▄▂▂▂▁▂▂▃▂▂▃▁▁▁▃▄▃▂▃▂▂▂▁▃▃▄▂▂▁▂▁▂▃▂▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,556 | 14,519 | +37 | 12,226 | 84,644 | stable (-0.05/hr) |
| Heap InUse | 188.6MB | 185.0MB | +3.6MB | 185.7MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1046.4MB | 1046.5MB | -0.1MB | 2594.1MB | 6883.9MB | |
| Heap Objects | 846,480 | 893,061 | -46581 | 825,818 | 17,165,538 | |

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
| 2026-06-05 | 238 | 16,116 | 245.5MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 6.61MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `reflect.unsafe_NewArray` | 3.0MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 2.14MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 11.38GB |
| 2 | `fmt.Sprintf` | 8.06GB |
| 3 | `reflect.growslice` | 7.78GB |
| 4 | `jackskj/carta.getUniqueId` | 7.73GB |
| 5 | `reflect.unsafe_New` | 6.52GB |
| 6 | `reflect.unsafe_NewArray` | 5.87GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.42GB |
| 8 | `fmt.(*buffer).writeString` | 4.96GB |
| 9 | `carta/value.NewCell` | 4.63GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 4.44GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 821.20MB | 811.53MB | 628.86MB | 0B |
| `evaluation.mergeMetadata` | 419.10MB | 415.60MB | 322.68MB | 0B |
| `local.(*Client).EvaluateV2` | 1.24GB | 1.22GB | 977.98MB | 0B |
| `local.topologicalSort` | 177.07MB | 176.56MB | 140.13MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.16GB | 1.15GB | 924.41MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 197.17MB | 196.13MB | 144.42MB | 0B |
| `localEvaluation.getMapOfValue` | 1.16GB | 1.15GB | 924.41MB | 0B |
| `utils.ParseFeatureFlag` | 1.16GB | 1.15GB | 926.46MB | 0B |

**Total FF alloc (current snapshot):** 6.29GB  |  **24h avg:** 4.87GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1480 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1480 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1480 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1131/1480 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1480 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.45MB | 1131/1480 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.85MB | 884/1480 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `fmt.Sprint` | 14.4MB | 3/1480 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1480 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1480 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1480 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1480 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1480 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1480 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1480 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.94GB | 1102/1480 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1480 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1480 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1480 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.78GB | 664/1480 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.9x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
