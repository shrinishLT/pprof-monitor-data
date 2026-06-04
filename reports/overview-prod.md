# Overview: prod
*Last updated: 2026-06-04 22:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T22:45 (1228 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,664 | avg: 11,439 | max: 84,644 | trend: decreasing (-9.43/hr))
```
▆▄▄▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▁▂▂▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 156.4MB | avg: 173.6MB | max: 2823.8MB | trend: stable (-0.11MB/hr))
```
▆▃▅▅▇▆▄▂▅▅▃▂▂▂▄▄▂▁▃▄▄▄█▆▅▁▂▄▂▂▂▁▁▂▁▂▂▂▁▁▁▂▂▂▁▁▂▂▁▁▃▂▂▂▁▂▃▃▃▃▃▂▂▂▅▄▅▃▃▃▃▃▂▂▁▁▂▂▁▃▄▆▆▄▆▂▂▂▂▁▃▂▁▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,664 | 16,042 | -1378 | 11,439 | 84,644 | decreasing (-9.43/hr) |
| Heap InUse | 156.4MB | 217.9MB | -61.5MB | 173.6MB | 2823.8MB | stable (-0.11MB/hr) |
| Heap Sys | 3848.6MB | 3845.9MB | +2.7MB | 2669.9MB | 6883.9MB | |
| Heap Objects | 374,073 | 855,438 | -481365 | 751,291 | 14,090,816 | |

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
| 2026-06-04 | 274 | 16,630 | 267.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 4.52MB |
| 6 | `bufio.NewReaderSize` | 4.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `reflect.unsafe_NewArray` | 3.01MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.18GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.42GB |
| 3 | `fmt.Sprintf` | 8.04GB |
| 4 | `segmentio/kafka-go.makePartitions` | 7.83GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 6.04GB |
| 6 | `database/sql.convertAssignRows` | 4.53GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.33GB |
| 8 | `strconv.appendQuotedWith` | 4.03GB |
| 9 | `reflect.unsafe_NewArray` | 4.0GB |
| 10 | `fmt.Sprint` | 3.91GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 632.65MB | 624.57MB | 445.39MB | 0B |
| `evaluation.mergeMetadata` | 328.58MB | 322.58MB | 229.03MB | 0B |
| `local.(*Client).EvaluateV2` | 985.72MB | 975.10MB | 697.01MB | 0B |
| `local.topologicalSort` | 135.06MB | 132.53MB | 96.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 867.66MB | 859.08MB | 615.49MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 205.15MB | 202.61MB | 144.21MB | 0B |
| `localEvaluation.getMapOfValue` | 867.66MB | 859.08MB | 615.49MB | 0B |
| `utils.ParseFeatureFlag` | 868.16MB | 859.58MB | 615.72MB | 0B |

**Total FF alloc (current snapshot):** 4.78GB  |  **24h avg:** 3.38GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1228 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1228 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 879/1228 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1228 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.28MB | 879/1228 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1228 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.28MB | 664/1228 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1228 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1228 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1228 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1228 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1228 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1228 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1228 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1228 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.81GB | 851/1228 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1228 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.98GB | 774/1228 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.07GB | 470/1228 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.18GB | 612/1228 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 439.8MB at 2026-05-19T17:02 (2.5x avg)
