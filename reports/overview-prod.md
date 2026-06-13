# Overview: prod
*Last updated: 2026-06-13 10:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T10:36 (3672 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 49,358 | avg: 14,567 | max: 84,644 | trend: INCREASING (+3.28/hr))
```
▁▁▁▁▆▃▄▂▂▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▄▂▅█
```

**Heap InUse** (current: 1168.9MB | avg: 240.1MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▇▃▃▄▂▃▂▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▄▂▅█
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 58%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 49,358 | 34,959 | +14399 | 14,567 | 84,644 | INCREASING (+3.28/hr) |
| Heap InUse | 1168.9MB | 787.6MB | +381.3MB | 240.1MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1317.2MB | 1360.4MB | -43.2MB | 2560.4MB | 6883.9MB | |
| Heap Objects | 5,494,571 | 3,889,691 | +1604880 | 1,034,004 | 17,165,538 | |

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
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 128 | 17,144 | 283.4MB | 1168.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 145.76MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 78.36MB |
| 3 | `bufio.NewReaderSize` | 78.32MB |
| 4 | `bufio.NewWriterSize` | 71.3MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 34.03MB |
| 7 | `runtime.mallocgc` | 22.51MB |
| 8 | `net/http.(*Transport).dialConn` | 20.0MB |
| 9 | `net/http.(*Transport).tryPutIdleConn` | 17.51MB |
| 10 | `crypto/tls.Client` | 15.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 31.21GB |
| 2 | `segmentio/kafka-go.makePartitions` | 30.99GB |
| 3 | `jackskj/carta.getUniqueId` | 27.7GB |
| 4 | `reflect.unsafe_New` | 25.1GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.97GB |
| 6 | `fmt.Sprintf` | 21.18GB |
| 7 | `fmt.(*buffer).writeString` | 18.44GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 18.07GB |
| 9 | `carta/value.NewCell` | 18.05GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.63GB | 1.62GB | 1.55GB | 0B |
| `evaluation.mergeMetadata` | 857.71MB | 854.71MB | 815.44MB | 0B |
| `local.(*Client).EvaluateV2` | 2.51GB | 2.50GB | 2.39GB | 0B |
| `local.topologicalSort` | 361.53MB | 360.52MB | 344.38MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.41GB | 2.40GB | 2.28GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 336.94MB | 336.94MB | 332.84MB | 0B |
| `localEvaluation.getMapOfValue` | 2.41GB | 2.40GB | 2.28GB | 0B |
| `utils.ParseFeatureFlag` | 2.42GB | 2.41GB | 2.29GB | 0B |

**Total FF alloc (current snapshot):** 12.90GB  |  **24h avg:** 12.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 49.43MB | 73/3672 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 44.97MB | 99/3672 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3323/3672 | `███████████░░░░ 74%` |
| 4 | `runtime.mallocgc` | 31.26MB | 3323/3672 | `█████████░░░░░░ 63%` |
| 5 | `database/sql.convertAssignRows` | 24.02MB | 123/3672 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3672 | `█████░░░░░░░░░░ 36%` |
| 7 | `bytes.growSlice` | 15.88MB | 2634/3672 | `████░░░░░░░░░░░ 32%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3672 | `████░░░░░░░░░░░ 28%` |
| 9 | `net/http.(*Transport).dialConn` | 13.25MB | 95/3672 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3672 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3672 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3672 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3672 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.96GB | 1923/3672 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 60.3GB | 2884/3672 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.16GB | 3046/3672 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 53.49GB | 2900/3672 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3672 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.17GB | 2664/3672 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.68GB | 2246/3672 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
