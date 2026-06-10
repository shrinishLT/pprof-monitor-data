# Overview: prod
*Last updated: 2026-06-11 05:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T05:15 (3032 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,303 | avg: 14,142 | max: 84,644 | trend: INCREASING (+3.78/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 310.3MB | avg: 229.9MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂▂▂▂▃▂▂▂▂▂▂▁▁▁▁▃▃▃▂▁▁▁▂▂▁▁▂▁▂▂▃▂▅▃▂▂▂▂▂▁▁▂▃▁▂▁▂▂▂▂▃▁▂▂▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,303 | 14,672 | +631 | 14,142 | 84,644 | INCREASING (+3.78/hr) |
| Heap InUse | 310.3MB | 265.5MB | +44.8MB | 229.9MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3344.8MB | 3344.1MB | +0.7MB | 2609.4MB | 6883.9MB | |
| Heap Objects | 1,459,187 | 1,205,100 | +254087 | 992,866 | 17,165,538 | |

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
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 64 | 14,893 | 269.4MB | 428.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 13.42MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 3.54MB |
| 7 | `bufio.NewWriterSize` | 3.04MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 9 | `reflect.unsafe_NewArray` | 2.5MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 153.43GB |
| 2 | `reflect.growslice` | 148.68GB |
| 3 | `jackskj/carta.getUniqueId` | 135.09GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 120.93GB |
| 5 | `reflect.unsafe_New` | 119.05GB |
| 6 | `fmt.Sprintf` | 110.9GB |
| 7 | `fmt.(*buffer).writeString` | 94.09GB |
| 8 | `carta/value.NewCell` | 84.94GB |
| 9 | `reflect.unsafe_NewArray` | 78.41GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 70.75GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.08GB | 8.08GB | 7.94GB | 0B |
| `evaluation.mergeMetadata` | 4.23GB | 4.23GB | 4.15GB | 0B |
| `local.(*Client).EvaluateV2` | 12.32GB | 12.32GB | 12.11GB | 0B |
| `local.topologicalSort` | 1.70GB | 1.70GB | 1.67GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.75GB | 11.74GB | 11.53GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.69GB | 1.69GB | 1.68GB | 0B |
| `localEvaluation.getMapOfValue` | 11.75GB | 11.74GB | 11.53GB | 0B |
| `utils.ParseFeatureFlag` | 11.77GB | 11.76GB | 11.55GB | 0B |

**Total FF alloc (current snapshot):** 63.28GB  |  **24h avg:** 62.16GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.39MB | 56/3032 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.2MB | 84/3032 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2683/3032 | `████████░░░░░░░ 58%` |
| 4 | `runtime.mallocgc` | 30.26MB | 2683/3032 | `███████░░░░░░░░ 48%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3032 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3032 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.37MB | 2081/3032 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.4MB | 61/3032 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3032 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3032 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3032 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3032 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3032 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 56.7GB | 1549/3032 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3032 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 47.77GB | 2406/3032 | `█████░░░░░░░░░░ 38%` |
| 7 | `reflect.growslice` | 46.96GB | 2244/3032 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3032 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 41.13GB | 2260/3032 | `████░░░░░░░░░░░ 32%` |
| 10 | `reflect.unsafe_New` | 40.26GB | 2024/3032 | `████░░░░░░░░░░░ 32%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
