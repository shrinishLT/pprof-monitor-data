# Overview: prod
*Last updated: 2026-06-15 10:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T10:26 (4246 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 24,688 | avg: 14,707 | max: 84,644 | trend: INCREASING (+2.45/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▅█▃
```

**Heap InUse** (current: 634.2MB | avg: 242.2MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▂▂▂▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▂▁▁▂▂▃▂▂▁▂▂▁▁▂▂▂▁▃▂▂▁▁▂▁▁▂▁▁▂▁▁▂▂▁▁▁▁▁▁▁▁▂▁▂▂▂▂▁▃▁▁▁▂▂▁▁▁▂▂▂▂▄▅▇█▇
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 29%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 24,688 | 39,064 | -14376 | 14,707 | 84,644 | INCREASING (+2.45/hr) |
| Heap InUse | 634.2MB | 661.6MB | -27.4MB | 242.2MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2346.4MB | 2323.2MB | +23.2MB | 2526.7MB | 6883.9MB | |
| Heap Objects | 2,925,023 | 1,878,774 | +1046249 | 1,041,160 | 17,165,538 | |

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
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 126 | 15,057 | 239.8MB | 661.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 53.31MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 32.36MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 27.13MB |
| 5 | `bufio.NewWriterSize` | 24.61MB |
| 6 | `bufio.NewReaderSize` | 19.07MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 9 | `net/http.(*Transport).dialConn` | 8.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 7.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 101.26GB |
| 2 | `reflect.growslice` | 99.0GB |
| 3 | `segmentio/kafka-go.makePartitions` | 96.44GB |
| 4 | `jackskj/carta.getUniqueId` | 88.91GB |
| 5 | `reflect.unsafe_New` | 78.16GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 75.32GB |
| 7 | `fmt.Sprintf` | 62.14GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 61.9GB |
| 9 | `fmt.(*buffer).writeString` | 60.99GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 57.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.58GB | 3.57GB | 3.44GB | 0B |
| `evaluation.mergeMetadata` | 1.84GB | 1.84GB | 1.77GB | 0B |
| `local.(*Client).EvaluateV2` | 5.50GB | 5.50GB | 5.30GB | 0B |
| `local.topologicalSort` | 797.34MB | 796.34MB | 765.11MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.44GB | 5.43GB | 5.21GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 625.65MB | 624.11MB | 615.52MB | 0B |
| `localEvaluation.getMapOfValue` | 5.44GB | 5.43GB | 5.21GB | 0B |
| `utils.ParseFeatureFlag` | 5.45GB | 5.44GB | 5.22GB | 0B |

**Total FF alloc (current snapshot):** 28.63GB  |  **24h avg:** 27.50GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.64MB | 87/4246 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.99MB | 120/4246 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3897/4246 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.31MB | 3897/4246 | `███████████░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.35MB | 142/4246 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4246 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.58MB | 3025/4246 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.27MB | 110/4246 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4246 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4246 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4246 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4246 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4246 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.55GB | 2435/4246 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 60.76GB | 3458/4246 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.73GB | 3620/4246 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.17GB | 3474/4246 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4246 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.03GB | 3238/4246 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.1GB | 2792/4246 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
