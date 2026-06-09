# Overview: prod
*Last updated: 2026-06-10 05:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T05:26 (2747 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,716 | avg: 13,952 | max: 84,644 | trend: INCREASING (+4.19/hr))
```
▁▁▁▂▁▁▁▁▃▁▁▂▁▁▁▂▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 255.2MB | avg: 223.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▂▂▂▁▁▁▄▂▁▃▂▁▁▃▃▁▂▂▁▄▃▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,716 | 15,661 | +55 | 13,952 | 84,644 | INCREASING (+4.19/hr) |
| Heap InUse | 255.2MB | 247.1MB | +8.1MB | 223.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3321.8MB | 3321.3MB | +0.5MB | 2534.4MB | 6883.9MB | |
| Heap Objects | 672,799 | 743,646 | -70847 | 974,217 | 17,165,538 | |

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
| 2026-06-10 | 66 | 17,025 | 322.9MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 14.58MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `reflect.growslice` | 6.09MB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 5.76MB |
| 8 | `bufio.NewWriterSize` | 5.54MB |
| 9 | `bufio.NewReaderSize` | 4.53MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 120.56GB |
| 2 | `reflect.growslice` | 114.22GB |
| 3 | `jackskj/carta.getUniqueId` | 101.76GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 93.53GB |
| 5 | `reflect.unsafe_New` | 90.3GB |
| 6 | `fmt.Sprintf` | 81.09GB |
| 7 | `fmt.(*buffer).writeString` | 72.89GB |
| 8 | `carta/value.NewCell` | 64.49GB |
| 9 | `reflect.unsafe_NewArray` | 61.58GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 50.01GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.97GB | 5.97GB | 5.86GB | 0B |
| `evaluation.mergeMetadata` | 3.15GB | 3.15GB | 3.09GB | 0B |
| `local.(*Client).EvaluateV2` | 9.12GB | 9.11GB | 8.95GB | 0B |
| `local.topologicalSort` | 1.27GB | 1.27GB | 1.25GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.69GB | 8.68GB | 8.52GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.26GB | 1.26GB | 1.25GB | 0B |
| `localEvaluation.getMapOfValue` | 8.69GB | 8.68GB | 8.52GB | 0B |
| `utils.ParseFeatureFlag` | 8.70GB | 8.70GB | 8.53GB | 0B |

**Total FF alloc (current snapshot):** 46.86GB  |  **24h avg:** 45.96GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 75.8MB | 45/2747 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.76MB | 76/2747 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2398/2747 | `███████░░░░░░░░ 48%` |
| 4 | `database/sql.convertAssignRows` | 29.15MB | 97/2747 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 27.86MB | 2398/2747 | `█████░░░░░░░░░░ 36%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2747 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 15.55MB | 1829/2747 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2747 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2747 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2747 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2747 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2747 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2747 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2747 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 44.66GB | 1264/2747 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2747 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 35.77GB | 2121/2747 | `████░░░░░░░░░░░ 28%` |
| 8 | `reflect.growslice` | 34.17GB | 1959/2747 | `████░░░░░░░░░░░ 27%` |
| 9 | `jackskj/carta.getUniqueId` | 29.66GB | 1975/2747 | `███░░░░░░░░░░░░ 23%` |
| 10 | `reflect.unsafe_New` | 29.35GB | 1739/2747 | `███░░░░░░░░░░░░ 23%` |

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
