# Overview: prod
*Last updated: 2026-06-09 20:12 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T20:12 (2636 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,124 | avg: 13,837 | max: 84,644 | trend: INCREASING (+4.19/hr))
```
▅▂▃▄▄▃▂▂▁▁▃▁▂▁▃▂▁▁▁▁▄▅▄▅▆▃▃▁▂▄▅▄▅▄▂▁▁▅▃▆█▄▃▃▃▂▃▁▂▄▂▁▁▃▃▄▁▁▂▂▂▂▁▁▁▁▁▂▁▁▂▁▃▂▂▂▁▂▄▅▅▄▃▁▂▃▃▃▅▂▂▂▄▅▇▃
```

**Heap InUse** (current: 314.3MB | avg: 219.4MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▅▂▂▃▂▃▂▃▂▁▃▂▁▃▃▄▂▃▇▄▃▆▄▄▃▃▂▁▃▅▃▃▆▃▂▂▂▅▂▃█▅▂▂▂▃▂▂▂▄▃▁▃▂▃▂▂▁▃▃▃▃▃▂▁▂▂▂▂▃▂▁▃▂▃▃▃▂▃▄▅▃▄▄▄▃▄▂▃▂▃▃▄▄▆▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,124 | 16,968 | -1844 | 13,837 | 84,644 | INCREASING (+4.19/hr) |
| Heap InUse | 314.3MB | 378.2MB | -63.9MB | 219.4MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3341.2MB | 3343.2MB | -2.0MB | 2501.4MB | 6883.9MB | |
| Heap Objects | 1,497,101 | 1,667,645 | -170544 | 960,117 | 17,165,538 | |

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
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 243 | 16,160 | 303.9MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 14.41MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.03MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 107.97GB |
| 2 | `reflect.growslice` | 104.74GB |
| 3 | `jackskj/carta.getUniqueId` | 93.48GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.19GB |
| 5 | `reflect.unsafe_New` | 82.87GB |
| 6 | `fmt.Sprintf` | 71.12GB |
| 7 | `fmt.(*buffer).writeString` | 67.24GB |
| 8 | `carta/value.NewCell` | 59.13GB |
| 9 | `reflect.unsafe_NewArray` | 55.21GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.85GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.27GB | 5.26GB | 5.02GB | 0B |
| `evaluation.mergeMetadata` | 2.77GB | 2.76GB | 2.63GB | 0B |
| `local.(*Client).EvaluateV2` | 8.05GB | 8.03GB | 7.67GB | 0B |
| `local.topologicalSort` | 1.12GB | 1.12GB | 1.07GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.66GB | 7.64GB | 7.33GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.12GB | 1.12GB | 1.04GB | 0B |
| `localEvaluation.getMapOfValue` | 7.66GB | 7.64GB | 7.33GB | 0B |
| `utils.ParseFeatureFlag` | 7.67GB | 7.66GB | 7.34GB | 0B |

**Total FF alloc (current snapshot):** 41.33GB  |  **24h avg:** 39.43GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.78MB | 42/2636 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 62.08MB | 69/2636 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2287/2636 | `██████░░░░░░░░░ 45%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2636 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.76MB | 2287/2636 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2636 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.32MB | 1735/2636 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2636 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2636 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2636 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2636 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2636 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2636 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2636 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2636 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.22GB | 1153/2636 | `████░░░░░░░░░░░ 32%` |
| 7 | `segmentio/kafka-go.makePartitions` | 31.44GB | 2010/2636 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.growslice` | 29.84GB | 1848/2636 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2636 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2636 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.4x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
