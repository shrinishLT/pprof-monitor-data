# Overview: prod
*Last updated: 2026-06-05 00:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T00:05 (1244 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,002 | avg: 11,485 | max: 84,644 | trend: decreasing (-8.63/hr))
```
▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁
```

**Heap InUse** (current: 195.8MB | avg: 174.3MB | max: 2823.8MB | trend: stable (-0.10MB/hr))
```
▁▁▂▃▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▂▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▂▂▁▁▁▁▁▂▃▄▄▃▄▂▁▁▂▁▂▂▁▁▂▁▁█▁▁▁▁▁▃▂▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,002 | 14,252 | +750 | 11,485 | 84,644 | decreasing (-8.63/hr) |
| Heap InUse | 195.8MB | 181.8MB | +14.0MB | 174.3MB | 2823.8MB | stable (-0.10MB/hr) |
| Heap Sys | 799.2MB | 799.2MB | +0.0MB | 2648.4MB | 6883.9MB | |
| Heap Objects | 830,134 | 1,027,350 | -197216 | 757,703 | 14,090,816 | |

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
| 2026-06-05 | 2 | 14,627 | 188.8MB | 195.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `bytes.growSlice` | 5.03MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 9 | `bufio.NewReaderSize` | 1.51MB |
| 10 | `reflect.unsafe_NewArray` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.76GB |
| 2 | `segmentio/kafka-go.makePartitions` | 1.44GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.1GB |
| 4 | `fmt.Sprintf` | 1.06GB |
| 5 | `jackskj/carta.getUniqueId` | 940.68MB |
| 6 | `reflect.growslice` | 782.64MB |
| 7 | `reflect.unsafe_NewArray` | 760.63MB |
| 8 | `reflect.unsafe_New` | 683.3MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 559.01MB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 529.2MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 106.35MB | 97.76MB | 376.26MB | 0B |
| `evaluation.mergeMetadata` | 59.01MB | 54.01MB | 194.26MB | 0B |
| `local.(*Client).EvaluateV2` | 147.70MB | 133.93MB | 585.63MB | 0B |
| `local.topologicalSort` | 20.18MB | 18.68MB | 80.07MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 133.39MB | 120.60MB | 516.11MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 23.53MB | 22.02MB | 120.86MB | 0B |
| `localEvaluation.getMapOfValue` | 133.39MB | 120.60MB | 516.11MB | 0B |
| `utils.ParseFeatureFlag` | 133.39MB | 120.60MB | 516.35MB | 0B |

**Total FF alloc (current snapshot):** 756.93MB  |  **24h avg:** 2.84GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.38MB | 41/1244 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.62MB | 25/1244 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 895/1244 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.49MB | 53/1244 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.11MB | 895/1244 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1244 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.13MB | 677/1244 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1244 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1244 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1244 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1244 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1244 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1244 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1244 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1244 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.16GB | 867/1244 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1244 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.66GB | 790/1244 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 10.83GB | 482/1244 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 9.95GB | 628/1244 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 439.8MB at 2026-05-19T17:02 (2.5x avg)
