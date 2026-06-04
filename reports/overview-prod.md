# Overview: prod
*Last updated: 2026-06-05 03:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T03:25 (1284 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,713 | avg: 11,590 | max: 84,644 | trend: decreasing (-6.90/hr))
```
▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 225.1MB | avg: 177.3MB | max: 3154.1MB | trend: stable (-0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,713 | 14,225 | +488 | 11,590 | 84,644 | decreasing (-6.90/hr) |
| Heap InUse | 225.1MB | 115.4MB | +109.7MB | 177.3MB | 3154.1MB | stable (-0.06MB/hr) |
| Heap Sys | 3178.2MB | 983.9MB | +2194.3MB | 2663.3MB | 6883.9MB | |
| Heap Objects | 1,367,941 | 302,698 | +1065243 | 779,081 | 17,165,538 | |

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
| 2026-06-05 | 42 | 14,833 | 265.8MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.51MB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.16MB |
| 5 | `bytes.growSlice` | 6.03MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `bufio.NewWriterSize` | 5.02MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 7.86GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 3.14GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.26GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.1GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.04GB |
| 6 | `database/sql.convertAssignRows` | 978.54MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 879.3MB |
| 8 | `reflect.unsafe_NewArray` | 665.84MB |
| 9 | `fmt.Sprintf` | 407.71MB |
| 10 | `reflect.MakeSlice` | 376.01MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 66.94MB | 60.36MB | 137.80MB | 0B |
| `evaluation.mergeMetadata` | 33.51MB | 31.51MB | 70.43MB | 0B |
| `local.(*Client).EvaluateV2` | 100.12MB | 90.41MB | 196.34MB | 0B |
| `local.topologicalSort` | 13.14MB | 12.13MB | 28.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 95.04MB | 87.36MB | 181.67MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 14.29MB | 11.73MB | 29.35MB | 0B |
| `localEvaluation.getMapOfValue` | 95.04MB | 87.36MB | 181.67MB | 0B |
| `utils.ParseFeatureFlag` | 95.54MB | 87.86MB | 181.76MB | 0B |

**Total FF alloc (current snapshot):** 513.62MB  |  **24h avg:** 1007.31MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.36MB | 27/1284 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.91MB | 43/1284 | `██████████████░ 96%` |
| 3 | `database/sql.convertAssignRows` | 37.77MB | 55/1284 | `███████░░░░░░░░ 47%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 935/1284 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 18.71MB | 935/1284 | `███░░░░░░░░░░░░ 23%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1284 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 14.68MB | 712/1284 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1284 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1284 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1284 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1284 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1284 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1284 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1284 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1284 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.92GB | 907/1284 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1284 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.03GB | 830/1284 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 10.23GB | 515/1284 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1284 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
