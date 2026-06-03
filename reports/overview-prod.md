# Overview: prod
*Last updated: 2026-06-04 02:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:20 (983 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,576 | avg: 10,112 | max: 84,644 | trend: decreasing (-38.62/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅
```

**Heap InUse** (current: 324.8MB | avg: 148.6MB | max: 1896.6MB | trend: decreasing (-0.59MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅▃▃▃▃▃▃▄▄▄▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,576 | 15,037 | +2539 | 10,112 | 84,644 | decreasing (-38.62/hr) |
| Heap InUse | 324.8MB | 252.7MB | +72.1MB | 148.6MB | 1896.6MB | decreasing (-0.59MB/hr) |
| Heap Sys | 857.3MB | 860.0MB | -2.7MB | 2552.5MB | 6883.9MB | |
| Heap Objects | 1,672,110 | 1,330,661 | +341449 | 635,254 | 8,100,802 | |

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
| 2026-06-04 | 29 | 15,505 | 211.9MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 19.6MB |
| 3 | `runtime.mallocgc` | 14.13MB |
| 4 | `bufio.NewReaderSize` | 12.05MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewWriterSize` | 9.04MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 2.18GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 3 | `reflect.growslice` | 1.77GB |
| 4 | `jackskj/carta.getUniqueId` | 1.66GB |
| 5 | `reflect.unsafe_New` | 1.49GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.35GB |
| 7 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.29GB |
| 8 | `fmt.(*buffer).writeString` | 1.1GB |
| 9 | `strconv.appendQuotedWith` | 1.08GB |
| 10 | `carta/value.NewCell` | 1.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 66.54MB | 62.03MB | 67.60MB | 0B |
| `evaluation.mergeMetadata` | 34.01MB | 31.01MB | 34.81MB | 0B |
| `local.(*Client).EvaluateV2` | 104.09MB | 98.57MB | 102.62MB | 0B |
| `local.topologicalSort` | 18.74MB | 17.73MB | 17.43MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 97.01MB | 91.49MB | 91.05MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 12.21MB | 12.21MB | 19.11MB | 0B |
| `localEvaluation.getMapOfValue` | 97.01MB | 91.49MB | 91.05MB | 0B |
| `utils.ParseFeatureFlag` | 97.01MB | 91.49MB | 91.29MB | 0B |

**Total FF alloc (current snapshot):** 526.62MB  |  **24h avg:** 514.96MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/983 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/983 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 634/983 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/983 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.74MB | 634/983 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.35MB | 443/983 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/983 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/983 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/983 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 627/983 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/983 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/983 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/983 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/983 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.58GB | 611/983 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/983 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/983 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.46GB | 560/983 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.78GB | 301/983 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.07GB | 416/983 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.2x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
