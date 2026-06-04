# Overview: prod
*Last updated: 2026-06-04 19:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T19:36 (1190 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,917 | avg: 11,287 | max: 84,644 | trend: decreasing (-11.94/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▅█▇▇▇▄▂▃▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂
```

**Heap InUse** (current: 255.9MB | avg: 171.2MB | max: 2823.8MB | trend: stable (-0.14MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▃▅▅▅▄▅▃▃▃▂▃▃▄▄▂▂▂▂▃▃▃▂▂█▂▄▄▃▄▄▅▄▃▂▃▄▂▂▂▂▃▃▂▁▃▃▃▃▅▄▄▁▂▃▂▂▂▁▁▂▁▂▂▂▁▁▁▂▂▂▁▁▂▂▁▁▂▂▂▁▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,917 | 16,552 | -635 | 11,287 | 84,644 | decreasing (-11.94/hr) |
| Heap InUse | 255.9MB | 247.0MB | +8.9MB | 171.2MB | 2823.8MB | stable (-0.14MB/hr) |
| Heap Sys | 3859.2MB | 3859.5MB | -0.3MB | 2632.2MB | 6883.9MB | |
| Heap Objects | 1,250,460 | 931,162 | +319298 | 740,650 | 14,090,816 | |

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
| 2026-06-04 | 236 | 16,699 | 270.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.28MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 7.03MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `bufio.NewReaderSize` | 5.05MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `reflect.unsafe_NewArray` | 4.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 9.07GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 7.29GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.6GB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.5GB |
| 5 | `database/sql.convertAssignRows` | 2.58GB |
| 6 | `fmt.Sprintf` | 2.53GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.4GB |
| 8 | `reflect.unsafe_NewArray` | 1.81GB |
| 9 | `jackskj/carta.getUniqueId` | 1.66GB |
| 10 | `strconv.appendQuotedWith` | 1.29GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 313.42MB | 304.77MB | 301.38MB | 0B |
| `evaluation.mergeMetadata` | 160.04MB | 157.04MB | 157.16MB | 0B |
| `local.(*Client).EvaluateV2` | 493.13MB | 477.70MB | 467.74MB | 0B |
| `local.topologicalSort` | 71.85MB | 70.35MB | 67.90MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 440.12MB | 427.28MB | 429.12MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 99.14MB | 96.55MB | 81.06MB | 0B |
| `localEvaluation.getMapOfValue` | 440.12MB | 427.28MB | 429.12MB | 0B |
| `utils.ParseFeatureFlag` | 440.12MB | 427.28MB | 429.12MB | 0B |

**Total FF alloc (current snapshot):** 2.40GB  |  **24h avg:** 2.31GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1190 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1190 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 841/1190 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1190 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.63MB | 841/1190 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1190 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.25MB | 627/1190 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1190 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1190 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1190 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1190 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1190 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1190 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1190 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1190 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.99GB | 813/1190 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1190 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.6GB | 736/1190 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 11.54GB | 432/1190 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.48GB | 574/1190 | `█░░░░░░░░░░░░░░ 8%` |

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
