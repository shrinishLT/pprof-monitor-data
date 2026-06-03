# Overview: prod
*Last updated: 2026-06-04 02:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:40 (987 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,497 | avg: 10,133 | max: 84,644 | trend: decreasing (-37.89/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅
```

**Heap InUse** (current: 237.7MB | avg: 148.9MB | max: 1896.6MB | trend: decreasing (-0.57MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅▃▃▃▃▃▃▄▄▄▅▄▃▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,497 | 15,350 | +147 | 10,133 | 84,644 | decreasing (-37.89/hr) |
| Heap InUse | 237.7MB | 235.7MB | +2.0MB | 148.9MB | 1896.6MB | decreasing (-0.57MB/hr) |
| Heap Sys | 861.3MB | 862.0MB | -0.7MB | 2545.7MB | 6883.9MB | |
| Heap Objects | 1,108,235 | 1,224,172 | -115937 | 636,756 | 8,100,802 | |

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
| 2026-06-04 | 33 | 15,479 | 212.8MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.13MB |
| 3 | `bytes.growSlice` | 9.55MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `compress/flate.NewWriter` | 5.29MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 8 | `bufio.NewReaderSize` | 3.51MB |
| 9 | `bufio.NewWriterSize` | 3.51MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 2.58GB |
| 2 | `reflect.growslice` | 2.51GB |
| 3 | `jackskj/carta.getUniqueId` | 2.41GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 5 | `reflect.unsafe_New` | 2.11GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.76GB |
| 7 | `fmt.(*buffer).writeString` | 1.55GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.53GB |
| 9 | `carta/value.NewCell` | 1.52GB |
| 10 | `strconv.appendQuotedWith` | 1.29GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 78.75MB | 74.74MB | 68.21MB | 0B |
| `evaluation.mergeMetadata` | 39.51MB | 38.01MB | 35.07MB | 0B |
| `local.(*Client).EvaluateV2` | 125.60MB | 119.55MB | 104.10MB | 0B |
| `local.topologicalSort` | 23.31MB | 21.28MB | 17.81MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 117.52MB | 111.97MB | 92.93MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 14.23MB | 13.23MB | 18.55MB | 0B |
| `localEvaluation.getMapOfValue` | 117.52MB | 111.97MB | 92.93MB | 0B |
| `utils.ParseFeatureFlag` | 117.52MB | 111.97MB | 93.14MB | 0B |

**Total FF alloc (current snapshot):** 633.95MB  |  **24h avg:** 522.73MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/987 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/987 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 638/987 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/987 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.69MB | 638/987 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.3MB | 447/987 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/987 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/987 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/987 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 631/987 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/987 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/987 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/987 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/987 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.3GB | 615/987 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/987 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/987 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.46GB | 560/987 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.62GB | 305/987 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.96GB | 420/987 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.2x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
