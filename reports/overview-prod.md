# Overview: prod
*Last updated: 2026-06-10 02:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T02:45 (2715 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,251 | avg: 13,944 | max: 84,644 | trend: INCREASING (+4.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▂▁▁▁▂▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂▂▁▁▁▁▁
```

**Heap InUse** (current: 242.1MB | avg: 223.0MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▂▁▂▁▂▁▁▁▁▁▁▁▂▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▄▂▁▂▂▁▁▃▃▁▂▂▁▄▃▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃▃▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,251 | 15,521 | -270 | 13,944 | 84,644 | INCREASING (+4.30/hr) |
| Heap InUse | 242.1MB | 314.7MB | -72.6MB | 223.0MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3309.8MB | 3307.2MB | +2.6MB | 2525.2MB | 6883.9MB | |
| Heap Objects | 850,680 | 1,761,738 | -911058 | 971,922 | 17,165,538 | |

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
| 2026-06-10 | 34 | 19,297 | 389.0MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 10.55MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 9.07MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 4.05MB |
| 8 | `database/sql.convertAssignRows` | 3.5MB |
| 9 | `bufio.NewReaderSize` | 3.03MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 116.91GB |
| 2 | `reflect.growslice` | 108.09GB |
| 3 | `jackskj/carta.getUniqueId` | 97.17GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 91.64GB |
| 5 | `reflect.unsafe_New` | 86.09GB |
| 6 | `fmt.Sprintf` | 79.65GB |
| 7 | `fmt.(*buffer).writeString` | 69.25GB |
| 8 | `carta/value.NewCell` | 61.45GB |
| 9 | `reflect.unsafe_NewArray` | 59.7GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 49.1GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.83GB | 5.82GB | 5.70GB | 0B |
| `evaluation.mergeMetadata` | 3.06GB | 3.06GB | 3.00GB | 0B |
| `local.(*Client).EvaluateV2` | 8.89GB | 8.88GB | 8.70GB | 0B |
| `local.topologicalSort` | 1.24GB | 1.24GB | 1.21GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.46GB | 8.45GB | 8.28GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.25GB | 1.25GB | 1.22GB | 0B |
| `localEvaluation.getMapOfValue` | 8.46GB | 8.45GB | 8.28GB | 0B |
| `utils.ParseFeatureFlag` | 8.47GB | 8.46GB | 8.29GB | 0B |

**Total FF alloc (current snapshot):** 45.65GB  |  **24h avg:** 44.67GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 77.45MB | 44/2715 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 58.95MB | 73/2715 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2366/2715 | `███████░░░░░░░░ 47%` |
| 4 | `database/sql.convertAssignRows` | 29.71MB | 95/2715 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 27.55MB | 2366/2715 | `█████░░░░░░░░░░ 35%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2715 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 15.69MB | 1805/2715 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2715 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2715 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2715 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2715 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2715 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2715 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2715 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2715 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 43.44GB | 1232/2715 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 34.5GB | 2089/2715 | `████░░░░░░░░░░░ 27%` |
| 8 | `reflect.growslice` | 32.94GB | 1927/2715 | `███░░░░░░░░░░░░ 26%` |
| 9 | `jackskj/carta.getUniqueId` | 28.54GB | 1943/2715 | `███░░░░░░░░░░░░ 22%` |
| 10 | `reflect.unsafe_New` | 28.28GB | 1707/2715 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
