# Overview: prod
*Last updated: 2026-06-04 21:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T21:45 (1216 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,635 | avg: 11,400 | max: 84,644 | trend: decreasing (-10.10/hr))
```
▁▁▂▂▄▃▃▂▁▂▃▅▆▄▄▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅
```

**Heap InUse** (current: 302.3MB | avg: 173.1MB | max: 2823.8MB | trend: stable (-0.12MB/hr))
```
▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁▂▃▄▄▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,635 | 20,678 | -2043 | 11,400 | 84,644 | decreasing (-10.10/hr) |
| Heap InUse | 302.3MB | 413.1MB | -110.8MB | 173.1MB | 2823.8MB | stable (-0.12MB/hr) |
| Heap Sys | 3843.0MB | 3839.2MB | +3.8MB | 2658.3MB | 6883.9MB | |
| Heap Objects | 735,160 | 1,683,891 | -948731 | 748,665 | 14,090,816 | |

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
| 2026-06-04 | 262 | 16,686 | 269.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 27.77MB |
| 3 | `bufio.NewWriterSize` | 13.55MB |
| 4 | `runtime.mallocgc` | 12.01MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 6 | `bufio.NewReaderSize` | 9.56MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `compress/flate.NewWriter` | 4.41MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.15GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.87GB |
| 3 | `fmt.Sprintf` | 6.9GB |
| 4 | `segmentio/kafka-go.makePartitions` | 6.42GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 6.03GB |
| 6 | `database/sql.convertAssignRows` | 4.37GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.2GB |
| 8 | `jackskj/carta.getUniqueId` | 3.59GB |
| 9 | `strconv.appendQuotedWith` | 3.46GB |
| 10 | `fmt.Sprint` | 3.36GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 562.17MB | 555.56MB | 337.61MB | 0B |
| `evaluation.mergeMetadata` | 290.57MB | 288.07MB | 174.32MB | 0B |
| `local.(*Client).EvaluateV2` | 880.01MB | 868.74MB | 529.32MB | 0B |
| `local.topologicalSort` | 118.89MB | 117.36MB | 74.92MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 772.66MB | 759.84MB | 469.35MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 185.76MB | 185.26MB | 108.64MB | 0B |
| `localEvaluation.getMapOfValue` | 772.66MB | 759.84MB | 469.35MB | 0B |
| `utils.ParseFeatureFlag` | 773.16MB | 760.34MB | 469.45MB | 0B |

**Total FF alloc (current snapshot):** 4.25GB  |  **24h avg:** 2.57GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1216 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1216 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 867/1216 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1216 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.39MB | 867/1216 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1216 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.34MB | 653/1216 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1216 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1216 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1216 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1216 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1216 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1216 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1216 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1216 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.13GB | 839/1216 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1216 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.15GB | 762/1216 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.16GB | 458/1216 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.24GB | 600/1216 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
