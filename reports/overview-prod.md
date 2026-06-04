# Overview: prod
*Last updated: 2026-06-04 17:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T17:50 (1169 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,659 | avg: 11,219 | max: 84,644 | trend: decreasing (-13.30/hr))
```
▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 216.1MB | avg: 170.7MB | max: 2823.8MB | trend: stable (-0.16MB/hr))
```
▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁▁▁▁▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,659 | 15,902 | -243 | 11,219 | 84,644 | decreasing (-13.30/hr) |
| Heap InUse | 216.1MB | 231.5MB | -15.4MB | 170.7MB | 2823.8MB | stable (-0.16MB/hr) |
| Heap Sys | 964.7MB | 963.5MB | +1.2MB | 2642.4MB | 6883.9MB | |
| Heap Objects | 775,841 | 1,123,579 | -347738 | 737,885 | 14,090,816 | |

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
| 2026-06-04 | 215 | 16,859 | 277.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.7MB |
| 5 | `bufio.NewWriterSize` | 7.03MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `bufio.NewReaderSize` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.61GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 1.4GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.08GB |
| 4 | `fmt.Sprintf` | 1.06GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 1.03GB |
| 6 | `database/sql.convertAssignRows` | 679.06MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 658.01MB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 611.93MB |
| 9 | `jackskj/carta.getUniqueId` | 574.63MB |
| 10 | `reflect.unsafe_NewArray` | 562.16MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 121.85MB | 110.66MB | 380.46MB | 0B |
| `evaluation.mergeMetadata` | 67.52MB | 62.01MB | 196.88MB | 0B |
| `local.(*Client).EvaluateV2` | 182.86MB | 165.38MB | 585.80MB | 0B |
| `local.topologicalSort` | 27.35MB | 25.33MB | 82.90MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 166.62MB | 152.21MB | 545.99MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 35.71MB | 32.13MB | 92.57MB | 0B |
| `localEvaluation.getMapOfValue` | 166.62MB | 152.21MB | 545.99MB | 0B |
| `utils.ParseFeatureFlag` | 166.62MB | 152.21MB | 545.99MB | 0B |

**Total FF alloc (current snapshot):** 935.17MB  |  **24h avg:** 2.91GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1169 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1169 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 820/1169 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 32.21MB | 50/1169 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 19.85MB | 820/1169 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1169 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.49MB | 606/1169 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1169 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1169 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1169 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1169 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1169 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1169 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1169 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1169 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.89GB | 792/1169 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1169 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.03GB | 716/1169 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.03GB | 411/1169 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.79GB | 553/1169 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
