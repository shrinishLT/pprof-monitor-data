# Overview: prod
*Last updated: 2026-06-04 11:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T11:50 (1097 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,260 | avg: 10,860 | max: 84,644 | trend: decreasing (-20.28/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 155.0MB | avg: 163.5MB | max: 2823.8MB | trend: stable (-0.27MB/hr))
```
▁▁▁▁▁▁▂▄▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,260 | 14,534 | -274 | 10,860 | 84,644 | decreasing (-20.28/hr) |
| Heap InUse | 155.0MB | 171.7MB | -16.7MB | 163.5MB | 2823.8MB | stable (-0.27MB/hr) |
| Heap Sys | 1189.2MB | 1189.5MB | -0.3MB | 2643.8MB | 6883.9MB | |
| Heap Objects | 941,014 | 673,311 | +267703 | 702,949 | 14,090,816 | |

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
| 2026-06-04 | 143 | 16,941 | 276.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `regexp.(*bitState).reset` | 1.55MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.14GB |
| 2 | `reflect.growslice` | 1.13GB |
| 3 | `jackskj/carta.getUniqueId` | 953.66MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 879.23MB |
| 5 | `reflect.unsafe_New` | 773.35MB |
| 6 | `fmt.(*buffer).writeString` | 635.87MB |
| 7 | `carta/value.NewCell` | 586.04MB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 550.13MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 466.51MB |
| 10 | `segmentio/kafka-go.makePartitions` | 461.9MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 48.02MB | 39.49MB | 239.05MB | 0B |
| `evaluation.mergeMetadata` | 28.51MB | 22.51MB | 123.75MB | 0B |
| `local.(*Client).EvaluateV2` | 61.89MB | 51.84MB | 366.56MB | 0B |
| `local.topologicalSort` | 5.05MB | 4.55MB | 52.17MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 60.98MB | 49.38MB | 367.85MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 5.55MB | 5.55MB | 34.05MB | 0B |
| `localEvaluation.getMapOfValue` | 60.98MB | 49.38MB | 367.85MB | 0B |
| `utils.ParseFeatureFlag` | 60.98MB | 49.38MB | 368.35MB | 0B |

**Total FF alloc (current snapshot):** 331.94MB  |  **24h avg:** 1.87GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1097 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1097 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 748/1097 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1097 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.72MB | 748/1097 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1097 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.11MB | 536/1097 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1097 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1097 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.49MB | 341/1097 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1097 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1097 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1097 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1097 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1097 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.74GB | 721/1097 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1097 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.34GB | 652/1097 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.19GB | 349/1097 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.88GB | 482/1097 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.8x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
