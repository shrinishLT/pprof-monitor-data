# Overview: prod
*Last updated: 2026-06-04 14:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:05 (1124 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,223 | avg: 11,003 | max: 84,644 | trend: decreasing (-17.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 218.5MB | avg: 166.1MB | max: 2823.8MB | trend: stable (-0.23MB/hr))
```
▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,223 | 16,103 | +120 | 11,003 | 84,644 | decreasing (-17.36/hr) |
| Heap InUse | 218.5MB | 212.6MB | +5.9MB | 166.1MB | 2823.8MB | stable (-0.23MB/hr) |
| Heap Sys | 3414.5MB | 3413.6MB | +0.9MB | 2624.5MB | 6883.9MB | |
| Heap Objects | 659,002 | 565,325 | +93677 | 714,639 | 14,090,816 | |

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
| 2026-06-04 | 170 | 16,921 | 275.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 153.66MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 83.09MB |
| 3 | `database/sql.convertAssignRows` | 64.5MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `bytes.growSlice` | 16.61MB |
| 6 | `runtime.mallocgc` | 11.01MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `bufio.NewWriterSize` | 5.52MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 11.46GB |
| 2 | `reflect.growslice` | 5.63GB |
| 3 | `jackskj/carta.getUniqueId` | 5.22GB |
| 4 | `fmt.Sprintf` | 5.21GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 4.57GB |
| 6 | `reflect.unsafe_New` | 4.54GB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.58GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.31GB |
| 9 | `fmt.(*buffer).writeString` | 3.3GB |
| 10 | `carta/value.NewCell` | 3.24GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 301.86MB | 294.72MB | 222.44MB | 0B |
| `evaluation.mergeMetadata` | 160.54MB | 156.54MB | 117.54MB | 0B |
| `local.(*Client).EvaluateV2` | 461.17MB | 446.80MB | 337.26MB | 0B |
| `local.topologicalSort` | 64.77MB | 61.71MB | 47.26MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 431.56MB | 416.68MB | 327.86MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 73.13MB | 71.59MB | 40.50MB | 0B |
| `localEvaluation.getMapOfValue` | 431.56MB | 416.68MB | 327.86MB | 0B |
| `utils.ParseFeatureFlag` | 431.56MB | 416.68MB | 328.08MB | 0B |

**Total FF alloc (current snapshot):** 2.30GB  |  **24h avg:** 1.71GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.94MB | 38/1124 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.75MB | 23/1124 | `██████████████░ 93%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 775/1124 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 48/1124 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 20.35MB | 775/1124 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1124 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.31MB | 562/1124 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1124 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1124 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.47MB | 360/1124 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1124 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1124 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1124 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1124 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1124 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.38GB | 748/1124 | `████░░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1124 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.84GB | 672/1124 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 12.73GB | 367/1124 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.36GB | 509/1124 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
