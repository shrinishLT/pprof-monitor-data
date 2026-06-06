# Overview: prod
*Last updated: 2026-06-06 06:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T06:35 (1609 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,601 | avg: 12,518 | max: 84,644 | trend: INCREASING (+1.96/hr))
```
▁▁▁▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇▅▂▁▂▃▁▂▂▆▃▁▁▁▁▁▁▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 173.7MB | avg: 189.7MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▂▁▁▂▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▆▇▅▁▁▂▅█▇▃▁▃▄▂▃▂▆▅▃▁▂▃▁▂▅▄▂▂▂▁▂▂▂▂▁▁▁▂▁▁▁▁▁▃▃▁▁▁▁▂▃▁▄▄▁▂▁▁▁▁▂▂▂▂▂▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,601 | 15,448 | -847 | 12,518 | 84,644 | INCREASING (+1.96/hr) |
| Heap InUse | 173.7MB | 233.5MB | -59.8MB | 189.7MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1042.9MB | 1039.7MB | +3.2MB | 2469.3MB | 6883.9MB | |
| Heap Objects | 497,975 | 1,031,318 | -533343 | 838,054 | 17,165,538 | |

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
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 80 | 16,255 | 251.2MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.56MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `compress/flate.NewWriter` | 5.29MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `bufio.NewReaderSize` | 2.51MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 29.65GB |
| 2 | `reflect.growslice` | 27.6GB |
| 3 | `segmentio/kafka-go.makePartitions` | 26.19GB |
| 4 | `jackskj/carta.getUniqueId` | 25.66GB |
| 5 | `reflect.unsafe_New` | 22.15GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.02GB |
| 7 | `fmt.(*buffer).writeString` | 18.93GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 18.4GB |
| 9 | `carta/value.NewCell` | 15.74GB |
| 10 | `strconv.appendQuotedWith` | 14.35GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.45GB | 1.45GB | 1.37GB | 0B |
| `evaluation.mergeMetadata` | 766.69MB | 763.69MB | 729.25MB | 0B |
| `local.(*Client).EvaluateV2` | 2.23GB | 2.22GB | 2.11GB | 0B |
| `local.topologicalSort` | 324.45MB | 323.94MB | 307.71MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.13GB | 2.12GB | 2.02GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 311.26MB | 311.26MB | 300.72MB | 0B |
| `localEvaluation.getMapOfValue` | 2.13GB | 2.12GB | 2.02GB | 0B |
| `utils.ParseFeatureFlag` | 2.13GB | 2.13GB | 2.02GB | 0B |

**Total FF alloc (current snapshot):** 11.44GB  |  **24h avg:** 10.85GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1609 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1609 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1609 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1260/1609 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1609 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.06MB | 1260/1609 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.91MB | 989/1609 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1609 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1609 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1609 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1609 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1609 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1609 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1609 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1609 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1609 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1609 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1609 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 10.93GB | 793/1609 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.49GB | 320/1609 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
