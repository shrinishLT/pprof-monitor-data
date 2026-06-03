# Overview: prod
*Last updated: 2026-06-04 02:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:05 (980 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,026 | avg: 10,092 | max: 84,644 | trend: decreasing (-39.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅
```

**Heap InUse** (current: 222.9MB | avg: 148.2MB | max: 1896.6MB | trend: decreasing (-0.60MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅▃▃▃▃▃▃▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,026 | 15,331 | -305 | 10,092 | 84,644 | decreasing (-39.23/hr) |
| Heap InUse | 222.9MB | 204.4MB | +18.5MB | 148.2MB | 1896.6MB | decreasing (-0.60MB/hr) |
| Heap Sys | 860.3MB | 859.9MB | +0.4MB | 2557.7MB | 6883.9MB | |
| Heap Objects | 826,234 | 740,951 | +85283 | 633,449 | 8,100,802 | |

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
| 2026-06-04 | 26 | 15,347 | 203.5MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.13MB |
| 3 | `bytes.growSlice` | 10.06MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 2 | `fmt.Sprintf` | 1.84GB |
| 3 | `reflect.growslice` | 1.74GB |
| 4 | `jackskj/carta.getUniqueId` | 1.63GB |
| 5 | `reflect.unsafe_New` | 1.46GB |
| 6 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.25GB |
| 7 | `fmt.(*buffer).writeString` | 1.08GB |
| 8 | `carta/value.NewCell` | 1.05GB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.04GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.03GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 57.98MB | 53.94MB | 68.01MB | 0B |
| `evaluation.mergeMetadata` | 29.51MB | 27.51MB | 35.10MB | 0B |
| `local.(*Client).EvaluateV2` | 90.40MB | 83.28MB | 102.89MB | 0B |
| `local.topologicalSort` | 16.19MB | 15.18MB | 17.38MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 86.38MB | 79.80MB | 90.89MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 9.15MB | 8.61MB | 19.77MB | 0B |
| `localEvaluation.getMapOfValue` | 86.38MB | 79.80MB | 90.89MB | 0B |
| `utils.ParseFeatureFlag` | 86.38MB | 79.80MB | 91.15MB | 0B |

**Total FF alloc (current snapshot):** 462.36MB  |  **24h avg:** 516.10MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/980 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/980 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 631/980 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/980 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.77MB | 631/980 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.29MB | 440/980 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/980 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/980 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/980 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 624/980 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/980 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/980 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/980 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/980 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.8GB | 608/980 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/980 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/980 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.46GB | 560/980 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 14.91GB | 298/980 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.15GB | 413/980 | `█░░░░░░░░░░░░░░ 10%` |

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
