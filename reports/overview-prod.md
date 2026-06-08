# Overview: prod
*Last updated: 2026-06-09 05:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T05:20 (2458 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,705 | avg: 13,652 | max: 84,644 | trend: INCREASING (+4.21/hr))
```
▁▁▂▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▅▃▃▂▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁▁▁▁▁▅▂▁▁▁▁▁▁▃▂▁▃▂▁▁▃▃▂
```

**Heap InUse** (current: 230.8MB | avg: 212.8MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▂▂▂▃▃▅▄▁▂▃▂▃▁▃▂▂▂▂▂▃▂▁▁▁▂▃▂▃▁▂▃▂▂▁▂▁▁▃▃▂▂▂▂▂▃▁▃▃▃▂▃▁▅▆▃▃▄▃▃▂▂▂▁▃▁█▆▃▁▂▁▂▁▂▁▂▂▆▅▁▁▁▂▂▂▄▃▃▅▃▂▁▄▅▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,705 | 17,424 | -1719 | 13,652 | 84,644 | INCREASING (+4.21/hr) |
| Heap InUse | 230.8MB | 413.7MB | -182.9MB | 212.8MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3338.3MB | 3336.2MB | +2.1MB | 2441.4MB | 6883.9MB | |
| Heap Objects | 503,662 | 1,796,543 | -1292881 | 936,768 | 17,165,538 | |

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
| 2026-06-09 | 65 | 15,513 | 287.3MB | 527.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `reflect.growslice` | 12.43MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bytes.growSlice` | 8.54MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 8 | `bufio.NewWriterSize` | 4.53MB |
| 9 | `reflect.unsafe_New` | 3.5MB |
| 10 | `bufio.NewReaderSize` | 3.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 87.59GB |
| 2 | `reflect.growslice` | 78.18GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.87GB |
| 4 | `jackskj/carta.getUniqueId` | 69.6GB |
| 5 | `reflect.unsafe_New` | 61.71GB |
| 6 | `fmt.Sprintf` | 55.71GB |
| 7 | `fmt.(*buffer).writeString` | 50.14GB |
| 8 | `reflect.unsafe_NewArray` | 44.8GB |
| 9 | `carta/value.NewCell` | 44.07GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 37.71GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.83GB | 3.82GB | 3.70GB | 0B |
| `evaluation.mergeMetadata` | 1.99GB | 1.99GB | 1.93GB | 0B |
| `local.(*Client).EvaluateV2` | 5.82GB | 5.81GB | 5.62GB | 0B |
| `local.topologicalSort` | 821.78MB | 819.75MB | 789.87MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.61GB | 5.60GB | 5.39GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 764.75MB | 764.25MB | 756.59MB | 0B |
| `localEvaluation.getMapOfValue` | 5.61GB | 5.60GB | 5.39GB | 0B |
| `utils.ParseFeatureFlag` | 5.62GB | 5.61GB | 5.40GB | 0B |

**Total FF alloc (current snapshot):** 30.02GB  |  **24h avg:** 28.94GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2458 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2458 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2109/2458 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2458 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 24.76MB | 2109/2458 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2458 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.11MB | 1578/2458 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2458 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2458 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2458 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2458 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2458 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2458 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2458 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2458 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 32.02GB | 975/2458 | `███░░░░░░░░░░░░ 25%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2458 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2458 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 24.99GB | 1832/2458 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `reflect.growslice` | 22.67GB | 1670/2458 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
