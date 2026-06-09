# Overview: prod
*Last updated: 2026-06-09 14:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T14:10 (2564 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,927 | avg: 13,802 | max: 84,644 | trend: INCREASING (+4.39/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 324.6MB | avg: 217.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,927 | 15,574 | +353 | 13,802 | 84,644 | INCREASING (+4.39/hr) |
| Heap InUse | 324.6MB | 303.6MB | +21.0MB | 217.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3318.1MB | 3317.2MB | +0.9MB | 2477.8MB | 6883.9MB | |
| Heap Objects | 1,093,379 | 987,117 | +106262 | 955,218 | 17,165,538 | |

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
| 2026-06-09 | 171 | 16,616 | 313.0MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 32.54MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 7 | `bufio.NewWriterSize` | 5.54MB |
| 8 | `bufio.NewReaderSize` | 5.03MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 103.45GB |
| 2 | `segmentio/kafka-go.makePartitions` | 99.69GB |
| 3 | `jackskj/carta.getUniqueId` | 91.87GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 89.98GB |
| 5 | `reflect.unsafe_New` | 81.61GB |
| 6 | `fmt.(*buffer).writeString` | 66.17GB |
| 7 | `fmt.Sprintf` | 65.6GB |
| 8 | `carta/value.NewCell` | 58.31GB |
| 9 | `reflect.unsafe_NewArray` | 50.96GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.50GB | 4.49GB | 4.30GB | 0B |
| `evaluation.mergeMetadata` | 2.36GB | 2.35GB | 2.25GB | 0B |
| `local.(*Client).EvaluateV2` | 6.86GB | 6.85GB | 6.56GB | 0B |
| `local.topologicalSort` | 984.66MB | 982.62MB | 936.99MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.62GB | 6.61GB | 6.35GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 892.62MB | 889.57MB | 839.85MB | 0B |
| `localEvaluation.getMapOfValue` | 6.62GB | 6.61GB | 6.35GB | 0B |
| `utils.ParseFeatureFlag` | 6.63GB | 6.63GB | 6.36GB | 0B |

**Total FF alloc (current snapshot):** 35.43GB  |  **24h avg:** 33.91GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 82.26MB | 41/2564 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.56MB | 67/2564 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2215/2564 | `██████░░░░░░░░░ 44%` |
| 4 | `database/sql.convertAssignRows` | 30.8MB | 91/2564 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 25.99MB | 2215/2564 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2564 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.53MB | 1664/2564 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2564 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2564 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.75MB | 72/2564 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2564 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2564 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2564 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2564 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2564 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 36.9GB | 1081/2564 | `████░░░░░░░░░░░ 29%` |
| 7 | `segmentio/kafka-go.makePartitions` | 28.75GB | 1938/2564 | `███░░░░░░░░░░░░ 22%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2564 | `███░░░░░░░░░░░░ 22%` |
| 9 | `reflect.growslice` | 26.83GB | 1776/2564 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2564 | `███░░░░░░░░░░░░ 21%` |

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
