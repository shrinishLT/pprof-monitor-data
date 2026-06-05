# Overview: prod
*Last updated: 2026-06-05 21:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T21:05 (1495 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,148 | avg: 12,255 | max: 84,644 | trend: stable (+0.18/hr))
```
▄▃▃▃▂▂▂▂▂▂▃▂▂▁▂▂▁▂▂▂▂▃▃▃▂▂▁▂▁▁▂▁▂▂▁▂▆▅▅▄▆█▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▂▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▁▁▁▁▂▃▂▂
```

**Heap InUse** (current: 236.4MB | avg: 186.0MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▆▅▄▄▄▃▃▄▄▅▄▄▄▂▂▄▁▂▄▅▃▅▃▃▃▄▁▄▂▃▁▂▃▃▁▂▆▇▇▅▇█▇▆▂▄▂▂▂▁▂▂▃▂▂▃▁▁▁▃▄▃▂▃▂▂▂▁▃▃▄▂▂▁▂▁▂▃▂▂▃▃▃▅▆▂▃▂▄▄▃▁▆▅▃▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,148 | 15,189 | -41 | 12,255 | 84,644 | stable (+0.18/hr) |
| Heap InUse | 236.4MB | 195.0MB | +41.4MB | 186.0MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1047.9MB | 1049.1MB | -1.2MB | 2578.6MB | 6883.9MB | |
| Heap Objects | 1,402,637 | 603,290 | +799347 | 826,115 | 17,165,538 | |

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
| 2026-06-05 | 253 | 16,058 | 243.7MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `bytes.growSlice` | 3.02MB |
| 7 | `bufio.NewReaderSize` | 2.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 16.11GB |
| 2 | `jackskj/carta.getUniqueId` | 13.87GB |
| 3 | `reflect.growslice` | 13.33GB |
| 4 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 13.31GB |
| 5 | `segmentio/kafka-go.makePartitions` | 13.18GB |
| 6 | `reflect.unsafe_New` | 11.55GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.05GB |
| 8 | `fmt.(*buffer).writeString` | 9.38GB |
| 9 | `carta/value.NewCell` | 8.24GB |
| 10 | `strconv.appendQuotedWith` | 7.79GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 954.27MB | 943.55MB | 747.57MB | 0B |
| `evaluation.mergeMetadata` | 486.12MB | 481.62MB | 382.99MB | 0B |
| `local.(*Client).EvaluateV2` | 1.44GB | 1.43GB | 1.13GB | 0B |
| `local.topologicalSort` | 213.97MB | 211.95MB | 164.61MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.35GB | 1.33GB | 1.06GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 233.52MB | 232.48MB | 176.26MB | 0B |
| `localEvaluation.getMapOfValue` | 1.35GB | 1.33GB | 1.06GB | 0B |
| `utils.ParseFeatureFlag` | 1.35GB | 1.34GB | 1.07GB | 0B |

**Total FF alloc (current snapshot):** 7.33GB  |  **24h avg:** 5.76GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1495 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1495 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1495 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1146/1495 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1495 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.37MB | 1146/1495 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.8MB | 899/1495 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1495 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1495 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1495 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1495 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1495 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1495 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1495 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1495 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1495 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1495 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1495 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.48GB | 207/1495 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.84GB | 679/1495 | `█░░░░░░░░░░░░░░ 7%` |

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
