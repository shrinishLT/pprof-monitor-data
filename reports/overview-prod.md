# Overview: prod
*Last updated: 2026-06-04 01:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T01:25 (972 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 25,305 | avg: 10,049 | max: 84,644 | trend: decreasing (-40.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█
```

**Heap InUse** (current: 519.6MB | avg: 147.7MB | max: 1896.6MB | trend: decreasing (-0.62MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 29%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 25,305 | 14,184 | +11121 | 10,049 | 84,644 | decreasing (-40.73/hr) |
| Heap InUse | 519.6MB | 112.4MB | +407.2MB | 147.7MB | 1896.6MB | decreasing (-0.62MB/hr) |
| Heap Sys | 842.0MB | 894.4MB | -52.4MB | 2571.7MB | 6883.9MB | |
| Heap Objects | 1,821,042 | 355,313 | +1465729 | 631,482 | 8,100,802 | |

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
| 2026-06-04 | 18 | 15,403 | 200.0MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 70.42MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 30.64MB |
| 4 | `bufio.NewReaderSize` | 25.6MB |
| 5 | `bufio.NewWriterSize` | 21.58MB |
| 6 | `runtime.mallocgc` | 12.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 11.01MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `crypto/tls.Client` | 6.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.14GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 854.83MB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 561.29MB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 474.01MB |
| 5 | `fmt.Sprintf` | 435.86MB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 343.01MB |
| 7 | `database/sql.convertAssignRows` | 306.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 291.32MB |
| 9 | `strconv.appendQuotedWith` | 238.76MB |
| 10 | `fmt.Sprint` | 209.64MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 25.54MB | 17.86MB | 75.53MB | 0B |
| `evaluation.mergeMetadata` | 11.50MB | 8.50MB | 39.17MB | 0B |
| `local.(*Client).EvaluateV2` | 39.92MB | 30.69MB | 113.78MB | 0B |
| `local.topologicalSort` | 6.58MB | 5.57MB | 19.06MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 36.95MB | 27.72MB | 99.04MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 5.03MB | 4.51MB | 23.69MB | 0B |
| `localEvaluation.getMapOfValue` | 36.95MB | 27.72MB | 99.04MB | 0B |
| `utils.ParseFeatureFlag` | 36.95MB | 27.72MB | 99.38MB | 0B |

**Total FF alloc (current snapshot):** 199.42MB  |  **24h avg:** 568.70MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/972 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/972 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 623/972 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/972 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.87MB | 623/972 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.36MB | 432/972 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/972 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/972 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/972 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 616/972 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/972 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/972 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/972 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/972 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 46.38GB | 600/972 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/972 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/972 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.71GB | 553/972 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.29GB | 290/972 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.4GB | 405/972 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.2x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
