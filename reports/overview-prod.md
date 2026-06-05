# Overview: prod
*Last updated: 2026-06-05 05:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T05:55 (1314 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,714 | avg: 11,670 | max: 84,644 | trend: decreasing (-5.72/hr))
```
▃▂▂▂▂▁▁▁▄▁▁▂▁▂▂▂▃█▄▁▁▁▁▂▁▂▁▁▁▁▁▁▂▆▃▁▁▁▁▁▁▁▁▂▃▂▃▃▃▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▁▂▄▃▄▆▅▁▁▁▁▁▁▂▂▁▆▂▁▁▁▂▂▂▁▁▂▃▂▃
```

**Heap InUse** (current: 170.9MB | avg: 179.3MB | max: 3154.1MB | trend: stable (-0.04MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,714 | 15,172 | +542 | 11,670 | 84,644 | decreasing (-5.72/hr) |
| Heap InUse | 170.9MB | 150.7MB | +20.2MB | 179.3MB | 3154.1MB | stable (-0.04MB/hr) |
| Heap Sys | 4533.5MB | 4533.8MB | -0.3MB | 2695.6MB | 6883.9MB | |
| Heap Objects | 347,057 | 372,108 | -25051 | 796,023 | 17,165,538 | |

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
| 2026-06-05 | 72 | 14,948 | 266.9MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `reflect.growslice` | 20.8MB |
| 3 | `bytes.growSlice` | 10.55MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `runtime.mallocgc` | 7.51MB |
| 6 | `reflect.unsafe_New` | 7.5MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `carta/value.(*Cell).Scan` | 4.0MB |
| 9 | `bufio.NewReaderSize` | 3.53MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 20.65GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 8.18GB |
| 3 | `reflect.growslice` | 8.09GB |
| 4 | `jackskj/carta.getUniqueId` | 6.21GB |
| 5 | `reflect.unsafe_New` | 5.82GB |
| 6 | `fmt.(*buffer).writeString` | 5.56GB |
| 7 | `segmentio/kafka-go.makePartitions` | 4.76GB |
| 8 | `carta/value.NewCell` | 4.06GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.68GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 3.32GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 235.79MB | 231.20MB | 144.01MB | 0B |
| `evaluation.mergeMetadata` | 117.53MB | 115.03MB | 73.15MB | 0B |
| `local.(*Client).EvaluateV2` | 360.93MB | 353.71MB | 214.90MB | 0B |
| `local.topologicalSort` | 53.11MB | 52.61MB | 30.94MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 364.57MB | 356.32MB | 209.51MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 31.14MB | 31.14MB | 24.21MB | 0B |
| `localEvaluation.getMapOfValue` | 364.57MB | 356.32MB | 209.51MB | 0B |
| `utils.ParseFeatureFlag` | 365.57MB | 357.32MB | 210.12MB | 0B |

**Total FF alloc (current snapshot):** 1.85GB  |  **24h avg:** 1.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 99.07MB | 29/1314 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 81.93MB | 46/1314 | `████████████░░░ 82%` |
| 3 | `database/sql.convertAssignRows` | 41.93MB | 58/1314 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 965/1314 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 18.35MB | 965/1314 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1314 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.48MB | 737/1314 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1314 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1314 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1314 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1314 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1314 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1314 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1314 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1314 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.22GB | 937/1314 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1314 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.67GB | 860/1314 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.77GB | 543/1314 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.73GB | 176/1314 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
