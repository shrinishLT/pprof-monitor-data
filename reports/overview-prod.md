# Overview: prod
*Last updated: 2026-06-11 23:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T23:10 (3247 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 29,879 | avg: 14,310 | max: 84,644 | trend: INCREASING (+3.65/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▂▃▃▂▂▃▁▁▁▂▁▁▁▁▂▃▃▃▃▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▂▁▁▁▁▁▂▃▂▁▁▁▁▁▁▁▁▁▆▆█
```

**Heap InUse** (current: 732.8MB | avg: 236.0MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▁▂▁▂▁▂▁▁▂▂▂▁▁▁▁▄▂▁▁▁▁▁▁▁▃▂▁▂▂▂▂▂▂▂▂▁▁▂▃▄▄▃▃▄▂▃▂▃▁▁▁▁▃▃▃▄▄▃▁▂▁▁▁▁▁▁▁▁▁▂▃▄▃▃▄▁▂▁▁▂▄▃▃▁▁▁▁▂▁▁▁▁▅▅█
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 35%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 29,879 | 27,270 | +2609 | 14,310 | 84,644 | INCREASING (+3.65/hr) |
| Heap InUse | 732.8MB | 528.1MB | +204.7MB | 236.0MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3289.0MB | 3302.6MB | -13.6MB | 2657.0MB | 6883.9MB | |
| Heap Objects | 3,526,685 | 1,740,736 | +1785949 | 1,014,406 | 17,165,538 | |

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
| 2026-06-11 | 279 | 16,268 | 309.6MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 79.46MB |
| 2 | `runtime.mallocgc` | 50.47MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 34.66MB |
| 5 | `bufio.NewReaderSize` | 31.13MB |
| 6 | `bufio.NewWriterSize` | 24.62MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.51MB |
| 8 | `net/http.(*Transport).dialConn` | 13.0MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 179.07GB |
| 2 | `segmentio/kafka-go.makePartitions` | 178.19GB |
| 3 | `jackskj/carta.getUniqueId` | 162.98GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.57GB |
| 5 | `reflect.unsafe_New` | 143.56GB |
| 6 | `fmt.Sprintf` | 132.83GB |
| 7 | `fmt.(*buffer).writeString` | 112.65GB |
| 8 | `carta/value.NewCell` | 102.53GB |
| 9 | `reflect.unsafe_NewArray` | 90.9GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 82.22GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.91GB | 9.91GB | 9.71GB | 0B |
| `evaluation.mergeMetadata` | 5.18GB | 5.17GB | 5.07GB | 0B |
| `local.(*Client).EvaluateV2` | 15.09GB | 15.08GB | 14.78GB | 0B |
| `local.topologicalSort` | 2.09GB | 2.09GB | 2.05GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.37GB | 14.36GB | 14.09GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.09GB | 2.09GB | 2.04GB | 0B |
| `localEvaluation.getMapOfValue` | 14.37GB | 14.36GB | 14.09GB | 0B |
| `utils.ParseFeatureFlag` | 14.40GB | 14.38GB | 14.11GB | 0B |

**Total FF alloc (current snapshot):** 77.51GB  |  **24h avg:** 75.91GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3247 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.04MB | 88/3247 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2898/3247 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.76MB | 2898/3247 | `████████░░░░░░░ 54%` |
| 5 | `database/sql.convertAssignRows` | 27.04MB | 107/3247 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3247 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.65MB | 2272/3247 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3247 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.98MB | 73/3247 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3247 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3247 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3247 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3247 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 66.66GB | 1764/3247 | `███████░░░░░░░░ 53%` |
| 5 | `reflect.growslice` | 57.87GB | 2459/3247 | `██████░░░░░░░░░ 46%` |
| 6 | `segmentio/kafka-go.makePartitions` | 57.46GB | 2621/3247 | `██████░░░░░░░░░ 45%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3247 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 51.05GB | 2475/3247 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.55GB | 2239/3247 | `█████░░░░░░░░░░ 39%` |
| 10 | `fmt.(*buffer).writeString` | 44.39GB | 1986/3247 | `█████░░░░░░░░░░ 35%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
