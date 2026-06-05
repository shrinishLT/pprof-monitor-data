# Overview: prod
*Last updated: 2026-06-05 21:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T21:25 (1499 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,263 | avg: 12,262 | max: 84,644 | trend: stable (+0.24/hr))
```
▂▂▂▂▂▂▃▂▂▁▂▂▁▂▂▂▂▃▃▃▂▂▁▂▁▁▂▁▂▂▁▂▆▅▅▄▆█▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▂▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▁▁▁▁▂▃▂▂▂▁▂▁
```

**Heap InUse** (current: 162.1MB | avg: 186.0MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▄▃▃▄▄▅▄▄▄▂▂▄▁▂▄▅▃▅▃▃▃▄▁▄▂▃▁▂▃▃▁▂▆▇▇▅▇█▇▆▂▄▂▂▂▁▂▂▃▂▂▃▁▁▁▃▄▃▂▃▂▂▂▁▃▃▄▂▂▁▂▁▂▃▂▂▃▃▃▅▆▂▃▂▄▄▃▁▆▅▃▄▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,263 | 15,474 | -1211 | 12,262 | 84,644 | stable (+0.24/hr) |
| Heap InUse | 162.1MB | 182.7MB | -20.6MB | 186.0MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1050.2MB | 1051.0MB | -0.8MB | 2574.5MB | 6883.9MB | |
| Heap Objects | 924,638 | 431,402 | +493236 | 825,825 | 17,165,538 | |

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
| 2026-06-05 | 257 | 16,040 | 242.7MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `bufio.NewWriterSize` | 1.03MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.01MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 17.2GB |
| 2 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 14.83GB |
| 3 | `jackskj/carta.getUniqueId` | 14.5GB |
| 4 | `reflect.growslice` | 13.86GB |
| 5 | `segmentio/kafka-go.makePartitions` | 13.58GB |
| 6 | `reflect.unsafe_New` | 12.06GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.94GB |
| 8 | `fmt.(*buffer).writeString` | 9.88GB |
| 9 | `carta/value.NewCell` | 8.59GB |
| 10 | `strconv.appendQuotedWith` | 8.31GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 982.54MB | 977.99MB | 780.96MB | 0B |
| `evaluation.mergeMetadata` | 503.62MB | 501.12MB | 400.01MB | 0B |
| `local.(*Client).EvaluateV2` | 1.49GB | 1.48GB | 1.18GB | 0B |
| `local.topologicalSort` | 222.08MB | 220.04MB | 172.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.39GB | 1.39GB | 1.11GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 239.67MB | 238.17MB | 185.60MB | 0B |
| `localEvaluation.getMapOfValue` | 1.39GB | 1.39GB | 1.11GB | 0B |
| `utils.ParseFeatureFlag` | 1.40GB | 1.39GB | 1.11GB | 0B |

**Total FF alloc (current snapshot):** 7.57GB  |  **24h avg:** 6.02GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1499 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1499 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1499 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1150/1499 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1499 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.35MB | 1150/1499 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.79MB | 902/1499 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1499 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1499 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1499 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1499 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1499 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1499 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1499 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1499 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1499 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1499 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1499 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.51GB | 211/1499 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.89GB | 683/1499 | `█░░░░░░░░░░░░░░ 7%` |

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
