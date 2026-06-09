# Overview: prod
*Last updated: 2026-06-09 22:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T22:25 (2663 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,960 | avg: 13,858 | max: 84,644 | trend: INCREASING (+4.16/hr))
```
▁▁▂▂▂▂▂▁▁▁▂▁▂▃▂▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▂▁▁▁▂▂▃▁▂▆▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▃▂▁▁█▃▁▅
```

**Heap InUse** (current: 421.5MB | avg: 220.2MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▂▄▂▂▄▂▂▂▂▄▂▂▅▄▂▂▂▃▂▁▂▃▂▁▂▂▂▂▁▁▂▂▂▂▂▂▁▂▂▁▁▂▁▁▂▂▂▂▂▁▂▃▃▂▃▃▃▂▃▂▃▁▂▂▃▃▄▃▃▇▄▂▁▁▁▁▁▁▂▂▁▁▂▁▁▃▅▄▂▂▂█▃▁▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,960 | 14,350 | +5610 | 13,858 | 84,644 | INCREASING (+4.16/hr) |
| Heap InUse | 421.5MB | 237.8MB | +183.7MB | 220.2MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3326.4MB | 3328.0MB | -1.6MB | 2509.8MB | 6883.9MB | |
| Heap Objects | 1,392,048 | 935,025 | +457023 | 962,418 | 17,165,538 | |

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
| 2026-06-09 | 270 | 16,132 | 303.6MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `bytes.growSlice` | 40.74MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 17.08MB |
| 5 | `bufio.NewWriterSize` | 14.6MB |
| 6 | `bufio.NewReaderSize` | 14.07MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 10 | `compress/flate.NewWriter` | 4.41MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 110.92GB |
| 2 | `reflect.growslice` | 105.01GB |
| 3 | `jackskj/carta.getUniqueId` | 93.87GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.24GB |
| 5 | `reflect.unsafe_New` | 83.18GB |
| 6 | `fmt.Sprintf` | 73.81GB |
| 7 | `fmt.(*buffer).writeString` | 67.4GB |
| 8 | `carta/value.NewCell` | 59.33GB |
| 9 | `reflect.unsafe_NewArray` | 56.73GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.11GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.52GB | 5.51GB | 5.30GB | 0B |
| `evaluation.mergeMetadata` | 2.90GB | 2.90GB | 2.79GB | 0B |
| `local.(*Client).EvaluateV2` | 8.42GB | 8.42GB | 8.10GB | 0B |
| `local.topologicalSort` | 1.17GB | 1.17GB | 1.13GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.01GB | 8.01GB | 7.71GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.18GB | 1.18GB | 1.13GB | 0B |
| `localEvaluation.getMapOfValue` | 8.01GB | 8.01GB | 7.71GB | 0B |
| `utils.ParseFeatureFlag` | 8.03GB | 8.02GB | 7.72GB | 0B |

**Total FF alloc (current snapshot):** 43.25GB  |  **24h avg:** 41.57GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2663 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 61.25MB | 70/2663 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2314/2663 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2663 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.04MB | 2314/2663 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2663 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.32MB | 1760/2663 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.69MB | 52/2663 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2663 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2663 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2663 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2663 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2663 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2663 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2663 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 41.37GB | 1180/2663 | `████░░░░░░░░░░░ 33%` |
| 7 | `segmentio/kafka-go.makePartitions` | 32.47GB | 2037/2663 | `███░░░░░░░░░░░░ 25%` |
| 8 | `reflect.growslice` | 30.92GB | 1875/2663 | `███░░░░░░░░░░░░ 24%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2663 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2663 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.4x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
