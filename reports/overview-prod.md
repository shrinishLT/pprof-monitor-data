# Overview: prod
*Last updated: 2026-06-10 10:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T10:40 (2810 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 51,564 | avg: 14,027 | max: 84,644 | trend: INCREASING (+4.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▅▃▅▆█
```

**Heap InUse** (current: 918.8MB | avg: 225.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▃▃▄▅▄█▆
```

## Current Status

Goroutines: `████████████░░░░░░░░ 60%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 51,564 | 43,683 | +7881 | 14,027 | 84,644 | INCREASING (+4.23/hr) |
| Heap InUse | 918.8MB | 1132.6MB | -213.8MB | 225.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3201.3MB | 3232.5MB | -31.2MB | 2552.3MB | 6883.9MB | |
| Heap Objects | 2,063,850 | 5,417,190 | -3353340 | 979,966 | 17,165,538 | |

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
| 2026-06-10 | 129 | 17,164 | 317.5MB | 1132.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 193.02MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 84.39MB |
| 3 | `bufio.NewReaderSize` | 80.32MB |
| 4 | `bufio.NewWriterSize` | 79.33MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 33.53MB |
| 8 | `net/http.(*Transport).dialConn` | 21.0MB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.33MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 17.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 129.84GB |
| 2 | `segmentio/kafka-go.makePartitions` | 127.7GB |
| 3 | `jackskj/carta.getUniqueId` | 115.3GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 107.87GB |
| 5 | `reflect.unsafe_New` | 102.41GB |
| 6 | `fmt.Sprintf` | 87.01GB |
| 7 | `fmt.(*buffer).writeString` | 82.23GB |
| 8 | `carta/value.NewCell` | 73.12GB |
| 9 | `reflect.unsafe_NewArray` | 65.28GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 55.16GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.30GB | 6.30GB | 6.17GB | 0B |
| `evaluation.mergeMetadata` | 3.30GB | 3.30GB | 3.24GB | 0B |
| `local.(*Client).EvaluateV2` | 9.61GB | 9.60GB | 9.41GB | 0B |
| `local.topologicalSort` | 1.34GB | 1.34GB | 1.31GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.21GB | 9.20GB | 8.99GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.29GB | 1.29GB | 1.28GB | 0B |
| `localEvaluation.getMapOfValue` | 9.21GB | 9.20GB | 8.99GB | 0B |
| `utils.ParseFeatureFlag` | 9.22GB | 9.21GB | 9.00GB | 0B |

**Total FF alloc (current snapshot):** 49.48GB  |  **24h avg:** 48.39GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2810 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2810 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2461/2810 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2810 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.44MB | 2461/2810 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2810 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.74MB | 1877/2810 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.33MB | 58/2810 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2810 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2810 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2810 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2810 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2810 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2810 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 47.27GB | 1327/2810 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2810 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 38.32GB | 2184/2810 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.growslice` | 36.88GB | 2022/2810 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 32.05GB | 2038/2810 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.unsafe_New` | 31.66GB | 1802/2810 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
