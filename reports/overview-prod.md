# Overview: prod
*Last updated: 2026-06-10 10:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T10:25 (2807 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 29,040 | avg: 13,995 | max: 84,644 | trend: INCREASING (+4.10/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▅█▅
```

**Heap InUse** (current: 783.7MB | avg: 224.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▂▂▁▁▂▂▁▁▁▂▂▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▂▁▁▁▁▂▁▁▁▁▂▂▂▂▂▂▂▄▅▇█
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 34%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 29,040 | 37,907 | -8867 | 13,995 | 84,644 | INCREASING (+4.10/hr) |
| Heap InUse | 783.7MB | 720.4MB | +63.3MB | 224.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3268.5MB | 3264.0MB | +4.5MB | 2551.5MB | 6883.9MB | |
| Heap Objects | 3,811,850 | 2,474,602 | +1337248 | 977,604 | 17,165,538 | |

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
| 2026-06-10 | 126 | 16,511 | 303.3MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 81.41MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 52.24MB |
| 3 | `runtime.mallocgc` | 50.47MB |
| 4 | `bufio.NewReaderSize` | 38.66MB |
| 5 | `bufio.NewWriterSize` | 38.17MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 17.51MB |
| 8 | `crypto/tls.Client` | 9.51MB |
| 9 | `jackskj/carta.getUniqueId` | 9.5MB |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 127.67GB |
| 2 | `segmentio/kafka-go.makePartitions` | 127.33GB |
| 3 | `jackskj/carta.getUniqueId` | 113.48GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 105.59GB |
| 5 | `reflect.unsafe_New` | 100.69GB |
| 6 | `fmt.Sprintf` | 86.33GB |
| 7 | `fmt.(*buffer).writeString` | 80.86GB |
| 8 | `carta/value.NewCell` | 71.86GB |
| 9 | `reflect.unsafe_NewArray` | 65.09GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 54.4GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.29GB | 6.28GB | 6.15GB | 0B |
| `evaluation.mergeMetadata` | 3.30GB | 3.30GB | 3.23GB | 0B |
| `local.(*Client).EvaluateV2` | 9.59GB | 9.58GB | 9.38GB | 0B |
| `local.topologicalSort` | 1.33GB | 1.33GB | 1.30GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.18GB | 9.17GB | 8.96GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.29GB | 1.29GB | 1.28GB | 0B |
| `localEvaluation.getMapOfValue` | 9.18GB | 9.17GB | 8.96GB | 0B |
| `utils.ParseFeatureFlag` | 9.19GB | 9.19GB | 8.98GB | 0B |

**Total FF alloc (current snapshot):** 49.35GB  |  **24h avg:** 48.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2807 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2807 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2458/2807 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2807 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.41MB | 2458/2807 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2807 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.51MB | 1874/2807 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).dialConn` | 14.21MB | 56/2807 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2807 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2807 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2807 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2807 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2807 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2807 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 47.14GB | 1324/2807 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2807 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 38.2GB | 2181/2807 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.growslice` | 36.74GB | 2019/2807 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 31.93GB | 2035/2807 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.unsafe_New` | 31.54GB | 1799/2807 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
