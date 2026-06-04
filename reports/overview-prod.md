# Overview: prod
*Last updated: 2026-06-04 18:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T18:40 (1179 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,644 | avg: 11,252 | max: 84,644 | trend: decreasing (-12.64/hr))
```
█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 224.9MB | avg: 170.8MB | max: 2823.8MB | trend: stable (-0.15MB/hr))
```
█▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▂▁▁▄▁▂▂▁▂▂▃▂▂▁▂▂▁▁▁▁▂▂▁▁▁▂▂▂▃▂▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,644 | 15,108 | +536 | 11,252 | 84,644 | decreasing (-12.64/hr) |
| Heap InUse | 224.9MB | 180.0MB | +44.9MB | 170.8MB | 2823.8MB | stable (-0.15MB/hr) |
| Heap Sys | 959.5MB | 961.1MB | -1.6MB | 2628.1MB | 6883.9MB | |
| Heap Objects | 1,087,392 | 828,355 | +259037 | 738,063 | 14,090,816 | |

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
| 2026-06-04 | 225 | 16,778 | 273.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.6MB |
| 5 | `bufio.NewWriterSize` | 6.02MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `bufio.NewReaderSize` | 3.02MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 3.0MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.45GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 2.64GB |
| 3 | `segmentio/kafka-go.makePartitions` | 2.22GB |
| 4 | `fmt.Sprintf` | 1.9GB |
| 5 | `jackskj/carta.getUniqueId` | 1.14GB |
| 6 | `reflect.unsafe_NewArray` | 1.14GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 1.05GB |
| 8 | `database/sql.convertAssignRows` | 1.05GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1021.02MB |
| 10 | `strconv.appendQuotedWith` | 973.47MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 204.32MB | 193.57MB | 346.11MB | 0B |
| `evaluation.mergeMetadata` | 109.53MB | 106.03MB | 179.51MB | 0B |
| `local.(*Client).EvaluateV2` | 319.37MB | 305.52MB | 534.68MB | 0B |
| `local.topologicalSort` | 48.10MB | 47.09MB | 76.56MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 287.90MB | 275.09MB | 495.64MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 63.26MB | 61.71MB | 87.23MB | 0B |
| `localEvaluation.getMapOfValue` | 287.90MB | 275.09MB | 495.64MB | 0B |
| `utils.ParseFeatureFlag` | 287.90MB | 275.09MB | 495.64MB | 0B |

**Total FF alloc (current snapshot):** 1.57GB  |  **24h avg:** 2.65GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1179 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1179 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 830/1179 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.63MB | 51/1179 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.75MB | 830/1179 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1179 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.37MB | 616/1179 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1179 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1179 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1179 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1179 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1179 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1179 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1179 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1179 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.42GB | 802/1179 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1179 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.8GB | 726/1179 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 11.79GB | 421/1179 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.63GB | 563/1179 | `█░░░░░░░░░░░░░░ 8%` |

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
