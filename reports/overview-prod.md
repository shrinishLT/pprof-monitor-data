# Overview: prod
*Last updated: 2026-06-05 19:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T19:55 (1482 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,253 | avg: 12,230 | max: 84,644 | trend: stable (-0.02/hr))
```
▁▁▁▁▁▁▁▁▃▃▃▂▂▄▃▃▃▂▂▂▂▂▂▃▂▂▁▂▂▁▂▂▂▂▃▃▃▂▂▁▂▁▁▂▁▂▂▁▂▆▅▅▄▆█▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▂▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▂▂
```

**Heap InUse** (current: 199.5MB | avg: 185.7MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▁▁▂▁▁▃▁▂▃▅▅▃▃▆▅▄▄▄▃▃▄▄▅▄▄▄▂▂▄▁▂▄▅▃▅▃▃▃▄▁▄▂▃▁▂▃▃▁▂▆▇▇▅▇█▇▆▂▄▂▂▂▁▂▂▃▂▂▃▁▁▁▃▄▃▂▃▂▂▂▁▃▃▄▂▂▁▂▁▂▃▂▂▃▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,253 | 15,060 | +193 | 12,230 | 84,644 | stable (-0.02/hr) |
| Heap InUse | 199.5MB | 186.7MB | +12.8MB | 185.7MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1046.8MB | 1046.6MB | +0.2MB | 2592.0MB | 6883.9MB | |
| Heap Objects | 688,656 | 615,278 | +73378 | 825,584 | 17,165,538 | |

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
| 2026-06-05 | 240 | 16,108 | 245.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.41MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 5.03MB |
| 7 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 3.31MB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 3.03MB |
| 9 | `bufio.NewWriterSize` | 3.01MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 11.59GB |
| 2 | `fmt.Sprintf` | 8.53GB |
| 3 | `reflect.growslice` | 8.21GB |
| 4 | `jackskj/carta.getUniqueId` | 8.21GB |
| 5 | `reflect.unsafe_New` | 6.88GB |
| 6 | `reflect.unsafe_NewArray` | 5.97GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.42GB |
| 8 | `fmt.(*buffer).writeString` | 5.29GB |
| 9 | `carta/value.NewCell` | 4.91GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 4.49GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 832.88MB | 826.83MB | 644.69MB | 0B |
| `evaluation.mergeMetadata` | 423.60MB | 422.10MB | 330.60MB | 0B |
| `local.(*Client).EvaluateV2` | 1.26GB | 1.25GB | 1001.83MB | 0B |
| `local.topologicalSort` | 183.64MB | 180.10MB | 143.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.18GB | 1.17GB | 946.33MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 201.81MB | 200.26MB | 148.65MB | 0B |
| `localEvaluation.getMapOfValue` | 1.18GB | 1.17GB | 946.33MB | 0B |
| `utils.ParseFeatureFlag` | 1.18GB | 1.17GB | 948.44MB | 0B |

**Total FF alloc (current snapshot):** 6.39GB  |  **24h avg:** 4.99GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1482 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1482 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1482 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1133/1482 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1482 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.44MB | 1133/1482 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.84MB | 886/1482 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1482 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 11.68MB | 4/1482 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1482 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1482 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1482 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1482 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1482 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1482 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.89GB | 1104/1482 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1482 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1482 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1482 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.78GB | 666/1482 | `█░░░░░░░░░░░░░░ 7%` |

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
