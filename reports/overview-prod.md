# Overview: prod
*Last updated: 2026-06-09 15:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T15:36 (2581 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,057 | avg: 13,813 | max: 84,644 | trend: INCREASING (+4.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 448.9MB | avg: 218.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,057 | 16,337 | +720 | 13,813 | 84,644 | INCREASING (+4.35/hr) |
| Heap InUse | 448.9MB | 284.4MB | +164.5MB | 218.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3343.2MB | 3338.5MB | +4.7MB | 2483.4MB | 6883.9MB | |
| Heap Objects | 1,763,371 | 679,494 | +1083877 | 956,032 | 17,165,538 | |

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
| 2026-06-09 | 188 | 16,510 | 311.3MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 17.65MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 9.05MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `bufio.NewReaderSize` | 7.54MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 4.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 103.91GB |
| 2 | `segmentio/kafka-go.makePartitions` | 101.69GB |
| 3 | `jackskj/carta.getUniqueId` | 92.46GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.08GB |
| 5 | `reflect.unsafe_New` | 82.09GB |
| 6 | `fmt.Sprintf` | 67.16GB |
| 7 | `fmt.(*buffer).writeString` | 66.58GB |
| 8 | `carta/value.NewCell` | 58.6GB |
| 9 | `reflect.unsafe_NewArray` | 51.99GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.67GB | 4.66GB | 4.45GB | 0B |
| `evaluation.mergeMetadata` | 2.45GB | 2.45GB | 2.33GB | 0B |
| `local.(*Client).EvaluateV2` | 7.14GB | 7.12GB | 6.79GB | 0B |
| `local.topologicalSort` | 1.00GB | 1.00GB | 972.99MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.88GB | 6.86GB | 6.56GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 947.25MB | 942.69MB | 880.16MB | 0B |
| `localEvaluation.getMapOfValue` | 6.88GB | 6.86GB | 6.56GB | 0B |
| `utils.ParseFeatureFlag` | 6.89GB | 6.87GB | 6.57GB | 0B |

**Total FF alloc (current snapshot):** 36.85GB  |  **24h avg:** 35.06GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 82.26MB | 41/2581 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 62.69MB | 68/2581 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2232/2581 | `██████░░░░░░░░░ 44%` |
| 4 | `database/sql.convertAssignRows` | 30.8MB | 91/2581 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.18MB | 2232/2581 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2581 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.51MB | 1681/2581 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2581 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2581 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2581 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2581 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2581 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2581 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2581 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2581 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 37.72GB | 1098/2581 | `████░░░░░░░░░░░ 30%` |
| 7 | `segmentio/kafka-go.makePartitions` | 29.37GB | 1955/2581 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2581 | `███░░░░░░░░░░░░ 22%` |
| 9 | `reflect.growslice` | 27.55GB | 1793/2581 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2581 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.4x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
