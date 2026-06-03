# Overview: prod
*Last updated: 2026-06-04 00:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:55 (966 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,461 | avg: 10,009 | max: 84,644 | trend: decreasing (-41.99/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇▆▇▇▆▆▆▆▇▆▆▆▆▆▆▆▇
```

**Heap InUse** (current: 187.3MB | avg: 147.1MB | max: 1896.6MB | trend: decreasing (-0.64MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▇▆▅▅▆▄▄▆▄█▆▃▃▃▅▄▄▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,461 | 15,119 | +342 | 10,009 | 84,644 | decreasing (-41.99/hr) |
| Heap InUse | 187.3MB | 176.7MB | +10.6MB | 147.1MB | 1896.6MB | decreasing (-0.64MB/hr) |
| Heap Sys | 2425.1MB | 2426.9MB | -1.8MB | 2579.1MB | 6883.9MB | |
| Heap Objects | 775,416 | 579,301 | +196115 | 629,341 | 8,100,802 | |

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
| 2026-06-04 | 12 | 14,855 | 180.4MB | 318.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 11.92MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `bytes.growSlice` | 9.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `bufio.NewWriterSize` | 5.53MB |
| 8 | `database/sql.convertAssignRows` | 5.5MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 10 | `compress/flate.NewWriter` | 3.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.6GB |
| 2 | `segmentio/kafka-go.makePartitions` | 1.73GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.41GB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.41GB |
| 5 | `fmt.Sprintf` | 1.19GB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.15GB |
| 7 | `reflect.unsafe_NewArray` | 907.89MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 711.52MB |
| 9 | `database/sql.convertAssignRows` | 594.03MB |
| 10 | `strconv.appendQuotedWith` | 582.27MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 106.10MB | 100.48MB | 83.76MB | 0B |
| `evaluation.mergeMetadata` | 57.01MB | 54.01MB | 43.43MB | 0B |
| `local.(*Client).EvaluateV2` | 159.25MB | 149.49MB | 125.58MB | 0B |
| `local.topologicalSort` | 26.35MB | 24.32MB | 20.89MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 143.96MB | 135.20MB | 108.60MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 29.61MB | 28.10MB | 26.86MB | 0B |
| `localEvaluation.getMapOfValue` | 143.96MB | 135.20MB | 108.60MB | 0B |
| `utils.ParseFeatureFlag` | 144.46MB | 135.70MB | 108.99MB | 0B |

**Total FF alloc (current snapshot):** 810.71MB  |  **24h avg:** 626.72MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/966 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/966 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 617/966 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/966 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.98MB | 617/966 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.32MB | 426/966 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/966 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/966 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 10.24MB | 4/966 | `███░░░░░░░░░░░░ 20%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 610/966 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/966 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/966 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/966 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/966 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 46.82GB | 594/966 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/966 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/966 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.92GB | 547/966 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.61GB | 284/966 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.55GB | 400/966 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.8x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.2x avg)
