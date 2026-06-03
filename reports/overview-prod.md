# Overview: prod
*Last updated: 2026-06-04 04:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T04:35 (1010 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,130 | avg: 10,255 | max: 84,644 | trend: decreasing (-33.96/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆
```

**Heap InUse** (current: 370.4MB | avg: 153.5MB | max: 2823.8MB | trend: stable (-0.48MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,130 | 15,765 | +2365 | 10,255 | 84,644 | decreasing (-33.96/hr) |
| Heap InUse | 370.4MB | 662.1MB | -291.7MB | 153.5MB | 2823.8MB | stable (-0.48MB/hr) |
| Heap Sys | 955.9MB | 726.7MB | +229.2MB | 2576.2MB | 6883.9MB | |
| Heap Objects | 1,514,301 | 3,329,463 | -1815162 | 658,046 | 14,090,816 | |

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
| 2026-06-04 | 56 | 15,469 | 269.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 26.65MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.05MB |
| 4 | `runtime.mallocgc` | 10.01MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 8.03MB |
| 7 | `bufio.NewWriterSize` | 7.53MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.5MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.9GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 763.03MB |
| 3 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 649.67MB |
| 4 | `fmt.Sprintf` | 648.86MB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 427.91MB |
| 6 | `jackskj/carta.getUniqueId` | 400.57MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 341.01MB |
| 8 | `reflect.growslice` | 340.87MB |
| 9 | `strconv.appendQuotedWith` | 321.5MB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 320.65MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.72MB | 5.12MB | 88.62MB | 0B |
| `evaluation.mergeMetadata` | 5.00MB | 2.00MB | 46.18MB | 0B |
| `local.(*Client).EvaluateV2` | 14.28MB | 5.66MB | 137.04MB | 0B |
| `local.topologicalSort` | 2.52MB | 0B | 22.23MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.28MB | 5.66MB | 130.24MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 15.21MB | 0B |
| `localEvaluation.getMapOfValue` | 14.28MB | 5.66MB | 130.24MB | 0B |
| `utils.ParseFeatureFlag` | 14.28MB | 5.66MB | 130.30MB | 0B |

**Total FF alloc (current snapshot):** 75.38MB  |  **24h avg:** 700.07MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 69.34MB | 28/1010 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1010 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 661/1010 | `███████░░░░░░░░ 52%` |
| 4 | `database/sql.convertAssignRows` | 34.25MB | 36/1010 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.42MB | 661/1010 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1010 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 13.2MB | 468/1010 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 18/1010 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1010 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1010 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1010 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1010 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1010 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1010 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 43.92GB | 638/1010 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1010 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1010 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.83GB | 581/1010 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.83GB | 328/1010 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1010 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.3x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
