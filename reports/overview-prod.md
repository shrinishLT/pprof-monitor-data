# Overview: prod
*Last updated: 2026-06-03 23:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T23:20 (949 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,025 | avg: 9,916 | max: 84,644 | trend: decreasing (-45.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█
```

**Heap InUse** (current: 299.4MB | avg: 146.3MB | max: 1896.6MB | trend: decreasing (-0.68MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,025 | 0 | +18025 | 9,916 | 84,644 | decreasing (-45.49/hr) |
| Heap InUse | 299.4MB | 0.0MB | +299.4MB | 146.3MB | 1896.6MB | decreasing (-0.68MB/hr) |
| Heap Sys | 3171.2MB | 0.0MB | +3171.2MB | 2581.8MB | 6883.9MB | |
| Heap Objects | 836,281 | 0 | +836281 | 626,252 | 8,100,802 | |

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
| 2026-06-03 | 49 | 663 | 10.4MB | 299.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 34.8MB |
| 3 | `bufio.NewReaderSize` | 12.05MB |
| 4 | `runtime.mallocgc` | 11.01MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.54MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewWriterSize` | 7.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.23GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 7.19GB |
| 3 | `fmt.Sprintf` | 5.41GB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.99GB |
| 5 | `database/sql.convertAssignRows` | 3.38GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.93GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 2.86GB |
| 8 | `fmt.Sprint` | 2.65GB |
| 9 | `strconv.appendQuotedWith` | 2.63GB |
| 10 | `reflect.unsafe_NewArray` | 2.04GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 336.90MB | 0B | 308.31MB | 0B |
| `evaluation.mergeMetadata` | 164.54MB | 0B | 150.04MB | 0B |
| `local.(*Client).EvaluateV2` | 515.21MB | 0B | 472.67MB | 0B |
| `local.topologicalSort` | 76.32MB | 0B | 70.27MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 428.92MB | 0B | 390.19MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 129.70MB | 0B | 121.80MB | 0B |
| `localEvaluation.getMapOfValue` | 428.92MB | 0B | 390.19MB | 0B |
| `utils.ParseFeatureFlag` | 429.42MB | 0B | 390.69MB | 0B |

**Total FF alloc (current snapshot):** 2.45GB  |  **24h avg:** 2.24GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/949 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/949 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 600/949 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.36MB | 32/949 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.28MB | 600/949 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.32MB | 414/949 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/949 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/949 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/949 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 593/949 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/949 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/949 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/949 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/949 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.1GB | 577/949 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/949 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/949 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.55GB | 530/949 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 16.55GB | 267/949 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.12GB | 383/949 | `█░░░░░░░░░░░░░░ 11%` |

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
