# Overview: prod
*Last updated: 2026-06-03 22:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T22:45 (947 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,444 | avg: 9,918 | max: 84,644 | trend: decreasing (-45.76/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 208.3MB | avg: 146.3MB | max: 1896.6MB | trend: decreasing (-0.69MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,444 | 0 | +14444 | 9,918 | 84,644 | decreasing (-45.76/hr) |
| Heap InUse | 208.3MB | 0.0MB | +208.3MB | 146.3MB | 1896.6MB | decreasing (-0.69MB/hr) |
| Heap Sys | 3169.2MB | 0.0MB | +3169.2MB | 2583.9MB | 6883.9MB | |
| Heap Objects | 1,296,740 | 0 | +1296740 | 626,692 | 8,100,802 | |

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
| 2026-06-03 | 47 | 307 | 4.4MB | 208.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `bytes.growSlice` | 4.46MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `aws/endpoints.init` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `bufio.NewReaderSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.19GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 7.15GB |
| 3 | `fmt.Sprintf` | 4.59GB |
| 4 | `database/sql.convertAssignRows` | 3.33GB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.19GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.89GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 2.84GB |
| 8 | `fmt.Sprint` | 2.27GB |
| 9 | `strconv.appendQuotedWith` | 2.24GB |
| 10 | `reflect.growslice` | 1.86GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 279.72MB | 0B | 279.72MB | 0B |
| `evaluation.mergeMetadata` | 135.53MB | 0B | 135.53MB | 0B |
| `local.(*Client).EvaluateV2` | 430.13MB | 0B | 430.13MB | 0B |
| `local.topologicalSort` | 64.21MB | 0B | 64.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 351.45MB | 0B | 351.45MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 113.90MB | 0B | 113.90MB | 0B |
| `localEvaluation.getMapOfValue` | 351.45MB | 0B | 351.45MB | 0B |
| `utils.ParseFeatureFlag` | 351.95MB | 0B | 351.95MB | 0B |

**Total FF alloc (current snapshot):** 2.03GB  |  **24h avg:** 2.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/947 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/947 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 599/947 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.36MB | 32/947 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.3MB | 599/947 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.27MB | 413/947 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/947 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/947 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/947 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 592/947 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/947 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/947 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/947 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/947 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.17GB | 576/947 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/947 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/947 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.59GB | 529/947 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 16.59GB | 266/947 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.14GB | 382/947 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (13.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (3.0x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.8x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.2x avg)
