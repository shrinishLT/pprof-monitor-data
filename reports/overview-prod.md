# Overview: prod
*Last updated: 2026-06-10 09:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T09:30 (2796 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,911 | avg: 13,964 | max: 84,644 | trend: INCREASING (+4.02/hr))
```
▃▁▁█▅▆▇▇▃▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 268.2MB | avg: 223.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▅▂▁█▆▅▇▆▄▄▃▂▂▂▁▁▁▁▂▂▁▂▁▁▂▁▃▂▂▂▂▂▁▁▁▁▂▂▂▁▂▁▁▁▁▁▂▂▂▁▁▂▂▁▂▂▂▂▃▁▂▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▂▂▂▁▁▁▁▂▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,911 | 15,097 | -186 | 13,964 | 84,644 | INCREASING (+4.02/hr) |
| Heap InUse | 268.2MB | 258.7MB | +9.5MB | 223.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3347.0MB | 3346.6MB | +0.4MB | 2548.5MB | 6883.9MB | |
| Heap Objects | 963,957 | 845,539 | +118418 | 975,054 | 17,165,538 | |

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
| 2026-06-10 | 115 | 16,009 | 291.1MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 7.04MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.07MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 3.04MB |
| 9 | `bufio.NewReaderSize` | 3.03MB |
| 10 | `reflect.growslice` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 126.11GB |
| 2 | `reflect.growslice` | 121.37GB |
| 3 | `jackskj/carta.getUniqueId` | 107.69GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 99.32GB |
| 5 | `reflect.unsafe_New` | 95.69GB |
| 6 | `fmt.Sprintf` | 84.32GB |
| 7 | `fmt.(*buffer).writeString` | 76.99GB |
| 8 | `carta/value.NewCell` | 68.25GB |
| 9 | `reflect.unsafe_NewArray` | 64.48GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 52.69GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.21GB | 6.21GB | 6.10GB | 0B |
| `evaluation.mergeMetadata` | 3.26GB | 3.26GB | 3.21GB | 0B |
| `local.(*Client).EvaluateV2` | 9.48GB | 9.47GB | 9.29GB | 0B |
| `local.topologicalSort` | 1.32GB | 1.31GB | 1.29GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.06GB | 9.05GB | 8.87GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.29GB | 1.29GB | 1.28GB | 0B |
| `localEvaluation.getMapOfValue` | 9.06GB | 9.05GB | 8.87GB | 0B |
| `utils.ParseFeatureFlag` | 9.07GB | 9.06GB | 8.89GB | 0B |

**Total FF alloc (current snapshot):** 48.75GB  |  **24h avg:** 47.80GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2796 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2796 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2447/2796 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2796 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.31MB | 2447/2796 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2796 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.36MB | 1863/2796 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2796 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2796 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2796 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2796 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2796 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2796 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2796 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 46.68GB | 1313/2796 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2796 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 37.75GB | 2170/2796 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.growslice` | 36.26GB | 2008/2796 | `████░░░░░░░░░░░ 28%` |
| 9 | `jackskj/carta.getUniqueId` | 31.51GB | 2024/2796 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.unsafe_New` | 31.13GB | 1788/2796 | `███░░░░░░░░░░░░ 24%` |

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
