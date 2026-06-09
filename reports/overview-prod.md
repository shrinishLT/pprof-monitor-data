# Overview: prod
*Last updated: 2026-06-09 06:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T06:55 (2477 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,341 | avg: 13,660 | max: 84,644 | trend: INCREASING (+4.15/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▅▃▃▂▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁▁▁▁▁▅▂▁▁▁▁▁▁▃▂▁▃▂▁▁▃▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 275.2MB | avg: 213.1MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▃▂▁▁▁▂▃▂▃▂▂▃▂▂▁▂▁▂▃▄▂▂▂▂▃▃▁▃▃▃▂▃▁▅▆▃▃▄▃▃▂▂▂▂▃▁█▆▃▁▂▁▂▁▂▁▂▂▆▅▁▂▁▂▂▂▄▃▃▅▃▂▁▄▅▂▂▃▃▂▁▁▁▃▃▁▃▂▂▃▂▂▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,341 | 14,959 | +382 | 13,660 | 84,644 | INCREASING (+4.15/hr) |
| Heap InUse | 275.2MB | 242.6MB | +32.6MB | 213.1MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3338.2MB | 3339.8MB | -1.6MB | 2448.3MB | 6883.9MB | |
| Heap Objects | 1,245,281 | 1,091,296 | +153985 | 937,960 | 17,165,538 | |

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
| 2026-06-09 | 84 | 15,349 | 280.3MB | 527.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewWriterSize` | 4.03MB |
| 7 | `bytes.growSlice` | 4.02MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 89.7GB |
| 2 | `reflect.growslice` | 85.4GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 76.19GB |
| 4 | `jackskj/carta.getUniqueId` | 75.02GB |
| 5 | `reflect.unsafe_New` | 66.73GB |
| 6 | `fmt.Sprintf` | 57.64GB |
| 7 | `fmt.(*buffer).writeString` | 55.23GB |
| 8 | `carta/value.NewCell` | 47.72GB |
| 9 | `reflect.unsafe_NewArray` | 45.89GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 39.56GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.92GB | 3.91GB | 3.80GB | 0B |
| `evaluation.mergeMetadata` | 2.04GB | 2.04GB | 1.98GB | 0B |
| `local.(*Client).EvaluateV2` | 5.96GB | 5.95GB | 5.77GB | 0B |
| `local.topologicalSort` | 844.61MB | 843.60MB | 813.36MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.76GB | 5.75GB | 5.56GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 775.41MB | 775.41MB | 763.99MB | 0B |
| `localEvaluation.getMapOfValue` | 5.76GB | 5.75GB | 5.56GB | 0B |
| `utils.ParseFeatureFlag` | 5.77GB | 5.76GB | 5.57GB | 512.56kB |

**Total FF alloc (current snapshot):** 30.78GB  |  **24h avg:** 29.76GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2477 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2477 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2128/2477 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2477 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 24.99MB | 2128/2477 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2477 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.02MB | 1594/2477 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2477 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2477 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2477 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2477 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2477 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2477 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2477 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2477 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 32.85GB | 994/2477 | `███░░░░░░░░░░░░ 26%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2477 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2477 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 25.64GB | 1851/2477 | `███░░░░░░░░░░░░ 20%` |
| 10 | `reflect.growslice` | 23.37GB | 1689/2477 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
