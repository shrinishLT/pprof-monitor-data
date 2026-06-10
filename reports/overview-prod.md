# Overview: prod
*Last updated: 2026-06-11 01:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T01:25 (2986 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,064 | avg: 14,129 | max: 84,644 | trend: INCREASING (+3.90/hr))
```
▁▁▁▂▂▁▁▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▃▁▂▂▂▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 276.8MB | avg: 229.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▁▁▂▃▁▂▃▄▃▂▃▃▂▂▁▂▂▃▃▂▃▃▂▁▂▃▂▃▂▁▄▂▂▃▃▃▄▃▁▁▂▄▂▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂▂▂▂▃▂▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,064 | 15,196 | -132 | 14,129 | 84,644 | INCREASING (+3.90/hr) |
| Heap InUse | 276.8MB | 287.4MB | -10.6MB | 229.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3330.5MB | 3329.8MB | +0.7MB | 2598.2MB | 6883.9MB | |
| Heap Objects | 1,392,670 | 1,580,954 | -188284 | 991,475 | 17,165,538 | |

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
| 2026-06-11 | 18 | 14,791 | 270.5MB | 298.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 6 | `bufio.NewReaderSize` | 3.05MB |
| 7 | `bufio.NewWriterSize` | 3.03MB |
| 8 | `bytes.growSlice` | 3.01MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 148.17GB |
| 2 | `reflect.growslice` | 139.9GB |
| 3 | `jackskj/carta.getUniqueId` | 126.05GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 113.18GB |
| 5 | `reflect.unsafe_New` | 111.34GB |
| 6 | `fmt.Sprintf` | 101.69GB |
| 7 | `fmt.(*buffer).writeString` | 87.86GB |
| 8 | `carta/value.NewCell` | 79.59GB |
| 9 | `reflect.unsafe_NewArray` | 75.7GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 60.67GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.80GB | 7.80GB | 7.65GB | 0B |
| `evaluation.mergeMetadata` | 4.08GB | 4.08GB | 4.01GB | 0B |
| `local.(*Client).EvaluateV2` | 11.90GB | 11.89GB | 11.66GB | 0B |
| `local.topologicalSort` | 1.65GB | 1.65GB | 1.61GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.32GB | 11.31GB | 11.08GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.67GB | 1.67GB | 1.63GB | 0B |
| `localEvaluation.getMapOfValue` | 11.32GB | 11.31GB | 11.08GB | 0B |
| `utils.ParseFeatureFlag` | 11.34GB | 11.33GB | 11.10GB | 0B |

**Total FF alloc (current snapshot):** 61.08GB  |  **24h avg:** 59.83GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 63.44MB | 55/2986 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 53.32MB | 82/2986 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2637/2986 | `████████░░░░░░░ 57%` |
| 4 | `runtime.mallocgc` | 29.91MB | 2637/2986 | `███████░░░░░░░░ 47%` |
| 5 | `database/sql.convertAssignRows` | 27.65MB | 104/2986 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2986 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.5MB | 2040/2986 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2986 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2986 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2986 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2986 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2986 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2986 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 54.91GB | 1503/2986 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2986 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 45.76GB | 2360/2986 | `█████░░░░░░░░░░ 36%` |
| 7 | `reflect.growslice` | 44.94GB | 2198/2986 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2986 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 39.29GB | 2214/2986 | `████░░░░░░░░░░░ 31%` |
| 10 | `reflect.unsafe_New` | 38.53GB | 1978/2986 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
