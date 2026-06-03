# Overview: prod
*Last updated: 2026-06-03 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T23:30 (950 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,648 | avg: 9,924 | max: 84,644 | trend: decreasing (-45.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇
```

**Heap InUse** (current: 257.7MB | avg: 146.4MB | max: 1896.6MB | trend: decreasing (-0.68MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁█▇
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,648 | 18,025 | -377 | 9,924 | 84,644 | decreasing (-45.25/hr) |
| Heap InUse | 257.7MB | 299.4MB | -41.7MB | 146.4MB | 1896.6MB | decreasing (-0.68MB/hr) |
| Heap Sys | 2438.0MB | 3171.2MB | -733.2MB | 2581.6MB | 6883.9MB | |
| Heap Objects | 609,941 | 836,281 | -226340 | 626,235 | 8,100,802 | |

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
| 2026-06-03 | 50 | 1,002 | 15.3MB | 299.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 20.6MB |
| 3 | `bufio.NewWriterSize` | 13.06MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.05MB |
| 5 | `runtime.mallocgc` | 11.01MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewReaderSize` | 8.55MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.37GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 932.09MB |
| 3 | `go-sql-driver/mysql.(*binaryRows).readRow` | 319.51MB |
| 4 | `database/sql.convertAssignRows` | 263.01MB |
| 5 | `fmt.Sprintf` | 110.31MB |
| 6 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 94.12MB |
| 7 | `fmt.Sprint` | 55.16MB |
| 8 | `strconv.appendQuotedWith` | 47.64MB |
| 9 | `segmentio/kafka-go.makePartitions` | 47.24MB |
| 10 | `go-sql-driver/mysql.parseBinaryDateTime` | 44.0MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.07MB | 336.90MB | 208.23MB | 0B |
| `evaluation.mergeMetadata` | 4.50MB | 164.54MB | 101.52MB | 0B |
| `local.(*Client).EvaluateV2` | 11.11MB | 515.21MB | 318.82MB | 0B |
| `local.topologicalSort` | 2.02MB | 76.32MB | 47.52MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.14MB | 428.92MB | 263.84MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.00MB | 129.70MB | 81.53MB | 0B |
| `localEvaluation.getMapOfValue` | 11.14MB | 428.92MB | 263.84MB | 0B |
| `utils.ParseFeatureFlag` | 11.14MB | 429.42MB | 264.17MB | 0B |

**Total FF alloc (current snapshot):** 60.12MB  |  **24h avg:** 1.51GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/950 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/950 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 601/950 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.36MB | 32/950 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.26MB | 601/950 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.34MB | 415/950 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/950 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/950 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/950 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 594/950 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/950 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/950 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/950 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/950 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.02GB | 578/950 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/950 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/950 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.51GB | 531/950 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 16.49GB | 268/950 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.08GB | 384/950 | `█░░░░░░░░░░░░░░ 11%` |

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
