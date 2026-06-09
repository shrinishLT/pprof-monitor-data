# Overview: prod
*Last updated: 2026-06-09 12:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T12:51 (2548 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,814 | avg: 13,795 | max: 84,644 | trend: INCREASING (+4.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▆▆▆█▆▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 281.7MB | avg: 217.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▃▄▄▄▆▆█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,814 | 14,891 | -77 | 13,795 | 84,644 | INCREASING (+4.44/hr) |
| Heap InUse | 281.7MB | 249.9MB | +31.8MB | 217.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3316.9MB | 3316.9MB | +0.0MB | 2472.5MB | 6883.9MB | |
| Heap Objects | 1,288,089 | 620,249 | +667840 | 953,391 | 17,165,538 | |

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
| 2026-06-09 | 155 | 16,795 | 315.1MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 4.72MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewWriterSize` | 3.03MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 9 | `bufio.NewReaderSize` | 2.52MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 101.17GB |
| 2 | `segmentio/kafka-go.makePartitions` | 97.88GB |
| 3 | `jackskj/carta.getUniqueId` | 89.86GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 89.69GB |
| 5 | `reflect.unsafe_New` | 79.86GB |
| 6 | `fmt.Sprintf` | 64.49GB |
| 7 | `fmt.(*buffer).writeString` | 64.42GB |
| 8 | `carta/value.NewCell` | 57.08GB |
| 9 | `reflect.unsafe_NewArray` | 50.04GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.66GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.36GB | 4.34GB | 4.17GB | 0B |
| `evaluation.mergeMetadata` | 2.28GB | 2.28GB | 2.18GB | 0B |
| `local.(*Client).EvaluateV2` | 6.66GB | 6.64GB | 6.36GB | 0B |
| `local.topologicalSort` | 953.32MB | 949.77MB | 904.08MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.43GB | 6.41GB | 6.16GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 856.33MB | 851.77MB | 809.45MB | 0B |
| `localEvaluation.getMapOfValue` | 6.43GB | 6.41GB | 6.16GB | 0B |
| `utils.ParseFeatureFlag` | 6.44GB | 6.43GB | 6.17GB | 0B |

**Total FF alloc (current snapshot):** 34.37GB  |  **24h avg:** 32.88GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2548 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2548 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2199/2548 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2548 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 25.81MB | 2199/2548 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2548 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.55MB | 1649/2548 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2548 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2548 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.75MB | 72/2548 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2548 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2548 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2548 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2548 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2548 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 36.1GB | 1065/2548 | `████░░░░░░░░░░░ 28%` |
| 7 | `segmentio/kafka-go.makePartitions` | 28.16GB | 1922/2548 | `███░░░░░░░░░░░░ 22%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2548 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2548 | `███░░░░░░░░░░░░ 21%` |
| 10 | `reflect.growslice` | 26.14GB | 1760/2548 | `███░░░░░░░░░░░░ 20%` |

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
