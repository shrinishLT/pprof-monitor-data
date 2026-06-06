# Overview: prod
*Last updated: 2026-06-06 05:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T05:55 (1601 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,162 | avg: 12,505 | max: 84,644 | trend: INCREASING (+1.89/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇▅▂▁▂▃▁▂▂▆▃▁▁▁▁▁▁▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁
```

**Heap InUse** (current: 171.8MB | avg: 189.6MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▁▁▁▂▁▁▁▁▂▁▁▂▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▆▇▅▁▁▂▅█▇▃▁▃▄▂▃▂▆▅▃▁▂▃▁▂▅▄▂▂▂▁▂▂▂▂▁▁▁▂▁▁▁▁▁▃▃▁▁▁▁▂▃▁▄▄▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,162 | 14,475 | -313 | 12,505 | 84,644 | INCREASING (+1.89/hr) |
| Heap InUse | 171.8MB | 140.0MB | +31.8MB | 189.6MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1041.3MB | 1041.3MB | +0.0MB | 2476.5MB | 6883.9MB | |
| Heap Objects | 967,310 | 429,498 | +537812 | 837,989 | 17,165,538 | |

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
| 2026-06-06 | 72 | 16,378 | 256.3MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `reflect.growslice` | 1.5MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 29.32GB |
| 2 | `reflect.growslice` | 27.56GB |
| 3 | `jackskj/carta.getUniqueId` | 25.63GB |
| 4 | `segmentio/kafka-go.makePartitions` | 25.25GB |
| 5 | `reflect.unsafe_New` | 22.12GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.02GB |
| 7 | `fmt.(*buffer).writeString` | 18.92GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 18.38GB |
| 9 | `carta/value.NewCell` | 15.71GB |
| 10 | `strconv.appendQuotedWith` | 14.18GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.41GB | 1.41GB | 1.35GB | 0B |
| `evaluation.mergeMetadata` | 749.68MB | 748.68MB | 716.20MB | 0B |
| `local.(*Client).EvaluateV2` | 2.17GB | 2.17GB | 2.07GB | 0B |
| `local.topologicalSort` | 316.33MB | 316.33MB | 302.30MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.08GB | 2.07GB | 1.98GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 304.58MB | 304.58MB | 297.18MB | 0B |
| `localEvaluation.getMapOfValue` | 2.08GB | 2.07GB | 1.98GB | 0B |
| `utils.ParseFeatureFlag` | 2.08GB | 2.08GB | 1.98GB | 0B |

**Total FF alloc (current snapshot):** 11.16GB  |  **24h avg:** 10.64GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1601 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1601 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1601 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1252/1601 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1601 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.07MB | 1252/1601 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.97MB | 981/1601 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1601 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1601 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1601 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1601 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1601 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1601 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1601 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1601 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1601 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1601 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1601 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 10.74GB | 785/1601 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.27GB | 312/1601 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
