# Overview: prod
*Last updated: 2026-06-09 22:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T22:55 (2669 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,530 | avg: 13,865 | max: 84,644 | trend: INCREASING (+4.16/hr))
```
▂▁▁▁▂▁▂▃▂▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▂▁▁▁▂▂▃▁▂▆▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▃▂▁▁█▃▁▅▃▂▁▅▄▁
```

**Heap InUse** (current: 216.0MB | avg: 220.4MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▂▂▂▄▂▂▅▃▂▂▂▂▁▁▁▃▂▁▂▁▂▂▁▁▂▂▂▂▂▂▁▂▁▁▁▂▁▁▂▁▂▂▂▁▂▃▃▂▃▂▃▂▃▂▂▁▂▂▃▃▄▃▃▇▃▂▁▁▁▁▁▁▂▂▁▁▂▁▁▃▅▄▂▂▂█▃▁▅▄▂▁▆▅▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,530 | 18,638 | -4108 | 13,865 | 84,644 | INCREASING (+4.16/hr) |
| Heap InUse | 216.0MB | 449.3MB | -233.3MB | 220.4MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3330.8MB | 3325.6MB | +5.2MB | 2511.6MB | 6883.9MB | |
| Heap Objects | 440,687 | 1,985,188 | -1544501 | 962,840 | 17,165,538 | |

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
| 2026-06-09 | 276 | 16,150 | 304.3MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 5.05MB |
| 6 | `bufio.NewReaderSize` | 4.53MB |
| 7 | `bufio.NewWriterSize` | 3.54MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 111.63GB |
| 2 | `reflect.growslice` | 105.06GB |
| 3 | `jackskj/carta.getUniqueId` | 93.99GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.25GB |
| 5 | `reflect.unsafe_New` | 83.25GB |
| 6 | `fmt.Sprintf` | 74.73GB |
| 7 | `fmt.(*buffer).writeString` | 67.42GB |
| 8 | `carta/value.NewCell` | 59.38GB |
| 9 | `reflect.unsafe_NewArray` | 57.09GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.12GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.56GB | 5.56GB | 5.36GB | 0B |
| `evaluation.mergeMetadata` | 2.92GB | 2.92GB | 2.82GB | 0B |
| `local.(*Client).EvaluateV2` | 8.49GB | 8.48GB | 8.19GB | 0B |
| `local.topologicalSort` | 1.18GB | 1.18GB | 1.14GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.08GB | 8.07GB | 7.79GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.19GB | 1.19GB | 1.15GB | 0B |
| `localEvaluation.getMapOfValue` | 8.08GB | 8.07GB | 7.79GB | 0B |
| `utils.ParseFeatureFlag` | 8.10GB | 8.09GB | 7.80GB | 0B |

**Total FF alloc (current snapshot):** 43.61GB  |  **24h avg:** 42.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2669 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 60.51MB | 71/2669 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2320/2669 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2669 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.1MB | 2320/2669 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2669 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.33MB | 1766/2669 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.48MB | 53/2669 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2669 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2669 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2669 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2669 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2669 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2669 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2669 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 41.61GB | 1186/2669 | `████░░░░░░░░░░░ 33%` |
| 7 | `segmentio/kafka-go.makePartitions` | 32.7GB | 2043/2669 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.growslice` | 31.16GB | 1881/2669 | `███░░░░░░░░░░░░ 24%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2669 | `███░░░░░░░░░░░░ 22%` |
| 10 | `jackskj/carta.getUniqueId` | 26.93GB | 1897/2669 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
