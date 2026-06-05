# Overview: prod
*Last updated: 2026-06-05 06:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T06:35 (1322 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,655 | avg: 11,690 | max: 84,644 | trend: decreasing (-5.44/hr))
```
▄▁▁▂▁▂▂▂▃█▄▁▁▁▁▂▁▂▁▁▁▁▁▁▂▆▃▁▁▁▁▁▁▁▁▂▃▂▃▃▃▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▁▂▄▃▄▆▅▁▁▁▁▁▁▂▂▁▆▂▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂▂▁▁
```

**Heap InUse** (current: 153.9MB | avg: 180.0MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,655 | 14,674 | -19 | 11,690 | 84,644 | decreasing (-5.44/hr) |
| Heap InUse | 153.9MB | 169.1MB | -15.2MB | 180.0MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 4533.6MB | 4534.5MB | -0.9MB | 2706.7MB | 6883.9MB | |
| Heap Objects | 560,412 | 626,546 | -66134 | 799,642 | 17,165,538 | |

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
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 80 | 14,942 | 269.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `bufio.NewReaderSize` | 2.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.45GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 20.03GB |
| 3 | `reflect.growslice` | 11.44GB |
| 4 | `jackskj/carta.getUniqueId` | 8.77GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.18GB |
| 6 | `reflect.unsafe_New` | 8.15GB |
| 7 | `fmt.(*buffer).writeString` | 7.96GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.17GB |
| 9 | `database/sql.convertAssignRows` | 6.6GB |
| 10 | `carta/value.NewCell` | 5.8GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 302.73MB | 297.14MB | 157.04MB | 0B |
| `evaluation.mergeMetadata` | 151.54MB | 148.04MB | 79.35MB | 0B |
| `local.(*Client).EvaluateV2` | 462.40MB | 452.26MB | 237.14MB | 512.01kB |
| `local.topologicalSort` | 69.32MB | 66.79MB | 34.34MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 458.95MB | 448.34MB | 234.49MB | 512.01kB |
| `localEvaluation.GetFeatureFlagPayload` | 50.01MB | 48.97MB | 24.78MB | 0B |
| `localEvaluation.getMapOfValue` | 458.95MB | 448.34MB | 234.49MB | 512.01kB |
| `utils.ParseFeatureFlag` | 459.95MB | 449.34MB | 235.27MB | 512.01kB |

**Total FF alloc (current snapshot):** 2.36GB  |  **24h avg:** 1.21GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1322 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1322 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1322 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 973/1322 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.26MB | 973/1322 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1322 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.4MB | 745/1322 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1322 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1322 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1322 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1322 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1322 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1322 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1322 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1322 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.28GB | 945/1322 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1322 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.68GB | 868/1322 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.77GB | 543/1322 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.62GB | 184/1322 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
