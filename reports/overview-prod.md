# Overview: prod
*Last updated: 2026-06-04 21:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T21:00 (1207 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,546 | avg: 11,357 | max: 84,644 | trend: decreasing (-10.76/hr))
```
▅▃▃▂▁▄▅▅▄▁▁▂▃▄▃▃▂▁▂▃▅▆▄▅▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▅▄▄▅█▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▄▄▅▄▂▂▃▁▂▁▁
```

**Heap InUse** (current: 169.0MB | avg: 172.4MB | max: 2823.8MB | trend: stable (-0.13MB/hr))
```
▅▃▃▂▁▂▃▃▄▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,546 | 14,733 | -187 | 11,357 | 84,644 | decreasing (-10.76/hr) |
| Heap InUse | 169.0MB | 233.8MB | -64.8MB | 172.4MB | 2823.8MB | stable (-0.13MB/hr) |
| Heap Sys | 3854.4MB | 3854.1MB | +0.3MB | 2649.5MB | 6883.9MB | |
| Heap Objects | 621,493 | 1,253,315 | -631822 | 746,106 | 14,090,816 | |

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
| 2026-06-04 | 253 | 16,668 | 269.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.55MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `bufio.NewReaderSize` | 4.55MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `reflect.growslice` | 2.64MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.05GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.53GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.96GB |
| 4 | `fmt.Sprintf` | 5.57GB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.38GB |
| 6 | `database/sql.convertAssignRows` | 4.22GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.05GB |
| 8 | `jackskj/carta.getUniqueId` | 3.27GB |
| 9 | `reflect.unsafe_NewArray` | 2.79GB |
| 10 | `strconv.appendQuotedWith` | 2.77GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 472.41MB | 460.67MB | 251.99MB | 0B |
| `evaluation.mergeMetadata` | 239.56MB | 233.56MB | 131.03MB | 0B |
| `local.(*Client).EvaluateV2` | 747.26MB | 728.26MB | 393.51MB | 0B |
| `local.topologicalSort` | 102.18MB | 99.65MB | 56.85MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 661.17MB | 642.64MB | 351.36MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 152.77MB | 150.27MB | 79.77MB | 0B |
| `localEvaluation.getMapOfValue` | 661.17MB | 642.64MB | 351.36MB | 0B |
| `utils.ParseFeatureFlag` | 661.67MB | 642.64MB | 351.37MB | 512.56kB |

**Total FF alloc (current snapshot):** 3.61GB  |  **24h avg:** 1.92GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1207 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1207 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 858/1207 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1207 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.47MB | 858/1207 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1207 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.27MB | 644/1207 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1207 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1207 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1207 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1207 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1207 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1207 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1207 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1207 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.38GB | 830/1207 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1207 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.29GB | 753/1207 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.26GB | 449/1207 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.31GB | 591/1207 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
