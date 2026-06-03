# Overview: prod
*Last updated: 2026-06-04 02:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:15 (982 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,037 | avg: 10,105 | max: 84,644 | trend: decreasing (-38.83/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅
```

**Heap InUse** (current: 252.7MB | avg: 148.4MB | max: 1896.6MB | trend: decreasing (-0.59MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅▃▃▃▃▃▃▄▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,037 | 18,002 | -2965 | 10,105 | 84,644 | decreasing (-38.83/hr) |
| Heap InUse | 252.7MB | 275.3MB | -22.6MB | 148.4MB | 1896.6MB | decreasing (-0.59MB/hr) |
| Heap Sys | 860.0MB | 859.3MB | +0.7MB | 2554.3MB | 6883.9MB | |
| Heap Objects | 1,330,661 | 671,989 | +658672 | 634,199 | 8,100,802 | |

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
| 2026-06-04 | 28 | 15,431 | 207.8MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 16.08MB |
| 3 | `runtime.mallocgc` | 14.13MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 6.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `bufio.NewReaderSize` | 3.51MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 2 | `fmt.Sprintf` | 2.09GB |
| 3 | `reflect.growslice` | 1.77GB |
| 4 | `jackskj/carta.getUniqueId` | 1.66GB |
| 5 | `reflect.unsafe_New` | 1.48GB |
| 6 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.29GB |
| 7 | `segmentio/kafka-go.makePartitions` | 1.2GB |
| 8 | `fmt.(*buffer).writeString` | 1.1GB |
| 9 | `carta/value.NewCell` | 1.07GB |
| 10 | `strconv.appendQuotedWith` | 1.03GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 62.03MB | 60.52MB | 67.63MB | 0B |
| `evaluation.mergeMetadata` | 31.01MB | 30.01MB | 34.84MB | 0B |
| `local.(*Client).EvaluateV2` | 98.57MB | 96.04MB | 102.57MB | 0B |
| `local.topologicalSort` | 17.73MB | 17.21MB | 17.39MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 91.49MB | 89.96MB | 90.88MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 12.21MB | 11.21MB | 19.31MB | 0B |
| `localEvaluation.getMapOfValue` | 91.49MB | 89.96MB | 90.88MB | 0B |
| `utils.ParseFeatureFlag` | 91.49MB | 89.96MB | 91.13MB | 0B |

**Total FF alloc (current snapshot):** 496.02MB  |  **24h avg:** 514.63MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/982 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/982 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 633/982 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/982 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.75MB | 633/982 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.34MB | 442/982 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/982 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/982 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/982 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 626/982 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/982 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/982 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/982 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/982 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.65GB | 610/982 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/982 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/982 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.46GB | 560/982 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.83GB | 300/982 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.09GB | 415/982 | `█░░░░░░░░░░░░░░ 10%` |

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
