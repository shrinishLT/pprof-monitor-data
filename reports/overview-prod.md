# Overview: prod
*Last updated: 2026-06-04 11:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T11:40 (1095 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,652 | avg: 10,853 | max: 84,644 | trend: decreasing (-20.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 169.0MB | avg: 163.5MB | max: 2823.8MB | trend: stable (-0.27MB/hr))
```
▁▁▁▁▁▁▁▁▂▄▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,652 | 14,789 | -137 | 10,853 | 84,644 | decreasing (-20.46/hr) |
| Heap InUse | 169.0MB | 191.9MB | -22.9MB | 163.5MB | 2823.8MB | stable (-0.27MB/hr) |
| Heap Sys | 1191.3MB | 1193.1MB | -1.8MB | 2646.4MB | 6883.9MB | |
| Heap Objects | 945,220 | 1,044,702 | -99482 | 702,759 | 14,090,816 | |

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
| 2026-06-04 | 141 | 16,977 | 277.7MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `bytes.growSlice` | 6.15MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.13GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 879.23MB |
| 3 | `reflect.growslice` | 827.26MB |
| 4 | `jackskj/carta.getUniqueId` | 673.61MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 550.13MB |
| 6 | `reflect.unsafe_New` | 549.75MB |
| 7 | `fmt.(*buffer).writeString` | 455.9MB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 454.4MB |
| 9 | `carta/value.NewCell` | 426.53MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 422.01MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 26.81MB | 19.20MB | 243.34MB | 0B |
| `evaluation.mergeMetadata` | 15.00MB | 10.50MB | 125.95MB | 0B |
| `local.(*Client).EvaluateV2` | 38.12MB | 27.95MB | 373.20MB | 0B |
| `local.topologicalSort` | 4.04MB | 3.53MB | 53.13MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 36.65MB | 26.99MB | 374.48MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 3.01MB | 2.51MB | 34.78MB | 0B |
| `localEvaluation.getMapOfValue` | 36.65MB | 26.99MB | 374.48MB | 0B |
| `utils.ParseFeatureFlag` | 36.65MB | 26.99MB | 375.00MB | 0B |

**Total FF alloc (current snapshot):** 196.95MB  |  **24h avg:** 1.91GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1095 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1095 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 746/1095 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1095 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.75MB | 746/1095 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1095 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.16MB | 534/1095 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1095 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1095 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.49MB | 341/1095 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1095 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1095 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1095 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1095 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1095 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.85GB | 719/1095 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1095 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.4GB | 650/1095 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.19GB | 349/1095 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.9GB | 481/1095 | `█░░░░░░░░░░░░░░ 9%` |

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
