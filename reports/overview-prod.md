# Overview: prod
*Last updated: 2026-06-09 14:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T14:55 (2573 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,182 | avg: 13,808 | max: 84,644 | trend: INCREASING (+4.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 380.2MB | avg: 217.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,182 | 15,623 | +559 | 13,808 | 84,644 | INCREASING (+4.37/hr) |
| Heap InUse | 380.2MB | 269.3MB | +110.9MB | 217.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3321.7MB | 3322.8MB | -1.1MB | 2480.7MB | 6883.9MB | |
| Heap Objects | 1,932,417 | 598,415 | +1334002 | 955,620 | 17,165,538 | |

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
| 2026-06-09 | 180 | 16,555 | 311.8MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 22.25MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 7.04MB |
| 7 | `bufio.NewReaderSize` | 5.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 103.61GB |
| 2 | `segmentio/kafka-go.makePartitions` | 100.74GB |
| 3 | `jackskj/carta.getUniqueId` | 92.07GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 89.99GB |
| 5 | `reflect.unsafe_New` | 81.78GB |
| 6 | `fmt.(*buffer).writeString` | 66.39GB |
| 7 | `fmt.Sprintf` | 66.38GB |
| 8 | `carta/value.NewCell` | 58.4GB |
| 9 | `reflect.unsafe_NewArray` | 51.51GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.0GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.58GB | 4.57GB | 4.38GB | 0B |
| `evaluation.mergeMetadata` | 2.40GB | 2.40GB | 2.29GB | 0B |
| `local.(*Client).EvaluateV2` | 7.00GB | 6.98GB | 6.68GB | 0B |
| `local.topologicalSort` | 1005.96MB | 1002.42MB | 955.63MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.75GB | 6.74GB | 6.46GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 919.82MB | 910.53MB | 859.95MB | 0B |
| `localEvaluation.getMapOfValue` | 6.75GB | 6.74GB | 6.46GB | 0B |
| `utils.ParseFeatureFlag` | 6.76GB | 6.75GB | 6.47GB | 0B |

**Total FF alloc (current snapshot):** 36.14GB  |  **24h avg:** 34.50GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 82.26MB | 41/2573 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.56MB | 67/2573 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2224/2573 | `██████░░░░░░░░░ 44%` |
| 4 | `database/sql.convertAssignRows` | 30.8MB | 91/2573 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.09MB | 2224/2573 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2573 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.53MB | 1673/2573 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2573 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2573 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2573 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2573 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2573 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2573 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2573 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2573 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 37.34GB | 1090/2573 | `████░░░░░░░░░░░ 29%` |
| 7 | `segmentio/kafka-go.makePartitions` | 29.08GB | 1947/2573 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2573 | `███░░░░░░░░░░░░ 22%` |
| 9 | `reflect.growslice` | 27.21GB | 1785/2573 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2573 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.4x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
