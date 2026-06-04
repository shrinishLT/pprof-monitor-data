# Overview: prod
*Last updated: 2026-06-04 19:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T19:55 (1194 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,549 | avg: 11,304 | max: 84,644 | trend: decreasing (-11.66/hr))
```
▁▁▁▁▁▁▁▃▅█▇▇▇▄▂▂▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▂▂
```

**Heap InUse** (current: 209.8MB | avg: 171.5MB | max: 2823.8MB | trend: stable (-0.14MB/hr))
```
▁▁▁▁▁▁▁▃▃▅▅▅▄▅▃▃▂▁▂▃▄▄▁▂▂▂▃▂▃▂▂█▂▄▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▃▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,549 | 16,373 | -824 | 11,304 | 84,644 | decreasing (-11.66/hr) |
| Heap InUse | 209.8MB | 271.4MB | -61.6MB | 171.5MB | 2823.8MB | stable (-0.14MB/hr) |
| Heap Sys | 3861.2MB | 3860.2MB | +1.0MB | 2636.3MB | 6883.9MB | |
| Heap Objects | 761,470 | 1,324,603 | -563133 | 742,118 | 14,090,816 | |

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
| 2026-06-04 | 240 | 16,690 | 270.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 12.02MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.04MB |
| 6 | `bufio.NewWriterSize` | 8.03MB |
| 7 | `bufio.NewReaderSize` | 6.05MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 9.07GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.07GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.95GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 3.6GB |
| 5 | `fmt.Sprintf` | 3.12GB |
| 6 | `database/sql.convertAssignRows` | 2.94GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.69GB |
| 8 | `reflect.unsafe_NewArray` | 2.04GB |
| 9 | `jackskj/carta.getUniqueId` | 1.73GB |
| 10 | `strconv.appendQuotedWith` | 1.57GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 348.49MB | 335.25MB | 283.47MB | 0B |
| `evaluation.mergeMetadata` | 177.54MB | 170.04MB | 147.74MB | 0B |
| `local.(*Client).EvaluateV2` | 543.15MB | 524.83MB | 440.40MB | 0B |
| `local.topologicalSort` | 77.44MB | 76.42MB | 64.11MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 483.92MB | 467.66MB | 402.07MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 109.47MB | 106.38MB | 78.71MB | 0B |
| `localEvaluation.getMapOfValue` | 483.92MB | 467.66MB | 402.07MB | 0B |
| `utils.ParseFeatureFlag` | 483.92MB | 467.66MB | 402.07MB | 0B |

**Total FF alloc (current snapshot):** 2.64GB  |  **24h avg:** 2.17GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1194 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1194 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 845/1194 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1194 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.59MB | 845/1194 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1194 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.25MB | 631/1194 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1194 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1194 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1194 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1194 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1194 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1194 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1194 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1194 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.84GB | 817/1194 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1194 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.52GB | 740/1194 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.46GB | 436/1194 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.44GB | 578/1194 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
