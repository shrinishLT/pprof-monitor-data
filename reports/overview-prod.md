# Overview: prod
*Last updated: 2026-06-04 21:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T21:25 (1212 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,184 | avg: 11,372 | max: 84,644 | trend: decreasing (-10.48/hr))
```
▄▅▅▄▁▁▂▃▄▃▃▂▁▂▃▅▆▄▅▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▅▄▄▅█▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▄▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃
```

**Heap InUse** (current: 273.6MB | avg: 172.5MB | max: 2823.8MB | trend: stable (-0.12MB/hr))
```
▂▃▃▄▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,184 | 14,651 | +2533 | 11,372 | 84,644 | decreasing (-10.48/hr) |
| Heap InUse | 273.6MB | 169.7MB | +103.9MB | 172.5MB | 2823.8MB | stable (-0.12MB/hr) |
| Heap Sys | 3851.5MB | 3854.0MB | -2.5MB | 2654.4MB | 6883.9MB | |
| Heap Objects | 1,300,115 | 892,031 | +408084 | 747,181 | 14,090,816 | |

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
| 2026-06-04 | 258 | 16,636 | 268.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 17.59MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `bufio.NewReaderSize` | 9.56MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 8.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.11GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.69GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.01GB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.97GB |
| 5 | `fmt.Sprintf` | 5.93GB |
| 6 | `database/sql.convertAssignRows` | 4.28GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.14GB |
| 8 | `jackskj/carta.getUniqueId` | 3.46GB |
| 9 | `reflect.unsafe_NewArray` | 3.08GB |
| 10 | `strconv.appendQuotedWith` | 2.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 518.23MB | 512.06MB | 299.43MB | 0B |
| `evaluation.mergeMetadata` | 264.06MB | 261.56MB | 154.89MB | 0B |
| `local.(*Client).EvaluateV2` | 817.56MB | 808.79MB | 468.86MB | 0B |
| `local.topologicalSort` | 111.30MB | 109.78MB | 66.95MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 719.22MB | 710.48MB | 417.02MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 171.67MB | 169.60MB | 95.60MB | 0B |
| `localEvaluation.getMapOfValue` | 719.22MB | 710.48MB | 417.02MB | 0B |
| `utils.ParseFeatureFlag` | 719.72MB | 710.98MB | 417.08MB | 0B |

**Total FF alloc (current snapshot):** 3.95GB  |  **24h avg:** 2.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1212 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1212 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 863/1212 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1212 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.42MB | 863/1212 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1212 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.2MB | 649/1212 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1212 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1212 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1212 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1212 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1212 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1212 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1212 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1212 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.24GB | 835/1212 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1212 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.21GB | 758/1212 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.2GB | 454/1212 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.27GB | 596/1212 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
