# Overview: prod
*Last updated: 2026-06-10 04:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T04:00 (2730 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,828 | avg: 13,948 | max: 84,644 | trend: INCREASING (+4.25/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▂▁▁▁▂▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 301.5MB | avg: 223.2MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▂▂▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▄▂▁▃▂▁▁▃▃▁▂▂▁▄▃▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,828 | 14,780 | +1048 | 13,948 | 84,644 | INCREASING (+4.25/hr) |
| Heap InUse | 301.5MB | 255.5MB | +46.0MB | 223.2MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3314.7MB | 3314.8MB | -0.1MB | 2529.5MB | 6883.9MB | |
| Heap Objects | 1,399,264 | 1,199,015 | +200249 | 973,484 | 17,165,538 | |

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
| 2026-06-10 | 49 | 17,871 | 349.6MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 9.55MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 6.04MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `bufio.NewReaderSize` | 2.52MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 118.61GB |
| 2 | `reflect.growslice` | 108.21GB |
| 3 | `jackskj/carta.getUniqueId` | 97.29GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 91.64GB |
| 5 | `reflect.unsafe_New` | 86.19GB |
| 6 | `fmt.Sprintf` | 80.18GB |
| 7 | `fmt.(*buffer).writeString` | 69.28GB |
| 8 | `carta/value.NewCell` | 61.51GB |
| 9 | `reflect.unsafe_NewArray` | 60.56GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 49.23GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.89GB | 5.89GB | 5.78GB | 0B |
| `evaluation.mergeMetadata` | 3.10GB | 3.10GB | 3.04GB | 0B |
| `local.(*Client).EvaluateV2` | 8.99GB | 8.99GB | 8.82GB | 0B |
| `local.topologicalSort` | 1.25GB | 1.25GB | 1.23GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.57GB | 8.56GB | 8.39GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.25GB | 1.25GB | 1.23GB | 0B |
| `localEvaluation.getMapOfValue` | 8.57GB | 8.56GB | 8.39GB | 0B |
| `utils.ParseFeatureFlag` | 8.58GB | 8.57GB | 8.41GB | 0B |

**Total FF alloc (current snapshot):** 46.21GB  |  **24h avg:** 45.30GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 77.45MB | 44/2730 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 58.19MB | 74/2730 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2381/2730 | `███████░░░░░░░░ 47%` |
| 4 | `database/sql.convertAssignRows` | 29.71MB | 95/2730 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 27.7MB | 2381/2730 | `█████░░░░░░░░░░ 35%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2730 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 15.63MB | 1816/2730 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2730 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2730 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2730 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2730 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2730 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2730 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2730 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 44.02GB | 1247/2730 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2730 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 35.1GB | 2104/2730 | `████░░░░░░░░░░░ 28%` |
| 8 | `reflect.growslice` | 33.52GB | 1942/2730 | `████░░░░░░░░░░░ 26%` |
| 9 | `jackskj/carta.getUniqueId` | 29.07GB | 1958/2730 | `███░░░░░░░░░░░░ 23%` |
| 10 | `reflect.unsafe_New` | 28.79GB | 1722/2730 | `███░░░░░░░░░░░░ 23%` |

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
