# Overview: prod
*Last updated: 2026-06-05 04:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T04:40 (1299 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,876 | avg: 11,632 | max: 84,644 | trend: decreasing (-6.28/hr))
```
▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▃▃▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 208.7MB | avg: 177.7MB | max: 3154.1MB | trend: stable (-0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,876 | 14,879 | -3 | 11,632 | 84,644 | decreasing (-6.28/hr) |
| Heap InUse | 208.7MB | 176.5MB | +32.2MB | 177.7MB | 3154.1MB | stable (-0.06MB/hr) |
| Heap Sys | 4532.8MB | 4532.3MB | +0.5MB | 2674.4MB | 6883.9MB | |
| Heap Objects | 1,181,479 | 811,470 | +370009 | 782,871 | 17,165,538 | |

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
| 2026-06-05 | 57 | 14,932 | 253.2MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `bytes.growSlice` | 8.04MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 8 | `bufio.NewReaderSize` | 2.54MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.36GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 5.69GB |
| 3 | `segmentio/kafka-go.makePartitions` | 2.96GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.95GB |
| 5 | `database/sql.convertAssignRows` | 1.73GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.58GB |
| 7 | `reflect.unsafe_NewArray` | 1.56GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.31GB |
| 9 | `fmt.Sprintf` | 1.29GB |
| 10 | `reflect.MakeSlice` | 867.02MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 161.20MB | 156.61MB | 143.36MB | 0B |
| `evaluation.mergeMetadata` | 82.02MB | 79.52MB | 72.61MB | 0B |
| `local.(*Client).EvaluateV2` | 243.28MB | 237.16MB | 209.19MB | 0B |
| `local.topologicalSort` | 35.90MB | 34.87MB | 30.46MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 238.24MB | 231.60MB | 197.03MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 26.04MB | 26.04MB | 28.62MB | 0B |
| `localEvaluation.getMapOfValue` | 238.24MB | 231.60MB | 197.03MB | 0B |
| `utils.ParseFeatureFlag` | 239.24MB | 232.60MB | 197.33MB | 0B |

**Total FF alloc (current snapshot):** 1.23GB  |  **24h avg:** 1.05GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 76.66MB | 28/1299 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 74.54MB | 45/1299 | `██████████████░ 97%` |
| 3 | `database/sql.convertAssignRows` | 36.87MB | 57/1299 | `███████░░░░░░░░ 48%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 950/1299 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 18.53MB | 950/1299 | `███░░░░░░░░░░░░ 24%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1299 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 14.59MB | 725/1299 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1299 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1299 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1299 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1299 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1299 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1299 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1299 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1299 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.5GB | 922/1299 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1299 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.82GB | 845/1299 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.97GB | 530/1299 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1299 | `█░░░░░░░░░░░░░░ 7%` |

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
