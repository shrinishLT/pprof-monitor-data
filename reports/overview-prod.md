# Overview: prod
*Last updated: 2026-06-05 13:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T13:50 (1409 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,614 | avg: 12,078 | max: 84,644 | trend: decreasing (-1.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 261.6MB | avg: 185.1MB | max: 3154.1MB | trend: stable (+0.01MB/hr))
```
▁▂▂▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▄▄▅▆▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,614 | 15,548 | +66 | 12,078 | 84,644 | decreasing (-1.38/hr) |
| Heap InUse | 261.6MB | 224.4MB | +37.2MB | 185.1MB | 3154.1MB | stable (+0.01MB/hr) |
| Heap Sys | 1054.6MB | 830.1MB | +224.5MB | 2672.0MB | 6883.9MB | |
| Heap Objects | 554,238 | 1,242,507 | -688269 | 822,652 | 17,165,538 | |

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
| 2026-06-05 | 167 | 16,521 | 266.0MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 215.67MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 83.12MB |
| 3 | `database/sql.convertAssignRows` | 81.5MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `runtime.mallocgc` | 10.58MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bytes.growSlice` | 8.54MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 8.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 5.41GB |
| 2 | `jackskj/carta.getUniqueId` | 4.81GB |
| 3 | `reflect.unsafe_New` | 4.28GB |
| 4 | `fmt.(*buffer).writeString` | 3.49GB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.36GB |
| 6 | `carta/value.NewCell` | 3.11GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.93GB |
| 8 | `fmt.Sprintf` | 2.79GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 2.41GB |
| 10 | `reflect.unsafe_NewArray` | 1.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 218.03MB | 208.91MB | 162.88MB | 0B |
| `evaluation.mergeMetadata` | 110.03MB | 106.03MB | 81.70MB | 0B |
| `local.(*Client).EvaluateV2` | 344.19MB | 328.86MB | 249.75MB | 0B |
| `local.topologicalSort` | 50.54MB | 47.50MB | 34.07MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 328.39MB | 316.65MB | 254.49MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 47.14MB | 42.53MB | 20.54MB | 0B |
| `localEvaluation.getMapOfValue` | 328.39MB | 316.65MB | 254.49MB | 0B |
| `utils.ParseFeatureFlag` | 328.89MB | 317.15MB | 254.55MB | 0B |

**Total FF alloc (current snapshot):** 1.71GB  |  **24h avg:** 1.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 98.34MB | 32/1409 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.97MB | 52/1409 | `███████████░░░░ 78%` |
| 3 | `database/sql.convertAssignRows` | 40.41MB | 65/1409 | `██████░░░░░░░░░ 41%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1060/1409 | `█████░░░░░░░░░░ 37%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1409 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.88MB | 1060/1409 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.31MB | 819/1409 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1409 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.06MB | 24/1409 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1409 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1409 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1409 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1409 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1409 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1409 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 32.81GB | 1031/1409 | `███░░░░░░░░░░░░ 26%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1409 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1409 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1409 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.15GB | 593/1409 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
