# Overview: prod
*Last updated: 2026-06-13 06:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T06:15 (3620 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,580 | avg: 14,531 | max: 84,644 | trend: INCREASING (+3.30/hr))
```
▁▁▅▅▃▄▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▃▂▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 218.1MB | avg: 239.5MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▄▅▃▃▄▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▄▃▃▃▄▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▃▄▄▂▃▂▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,580 | 15,035 | -455 | 14,531 | 84,644 | INCREASING (+3.30/hr) |
| Heap InUse | 218.1MB | 213.3MB | +4.8MB | 239.5MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1418.5MB | 1418.2MB | +0.3MB | 2576.8MB | 6883.9MB | |
| Heap Objects | 834,868 | 661,747 | +173121 | 1,029,847 | 17,165,538 | |

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
| 2026-06-13 | 76 | 17,206 | 285.5MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 23.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bytes.growSlice` | 4.52MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.54MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 25.04GB |
| 2 | `reflect.growslice` | 23.12GB |
| 3 | `jackskj/carta.getUniqueId` | 20.44GB |
| 4 | `reflect.unsafe_New` | 18.42GB |
| 5 | `fmt.Sprintf` | 17.84GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 17.82GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 14.7GB |
| 8 | `fmt.(*buffer).writeString` | 13.65GB |
| 9 | `carta/value.NewCell` | 13.28GB |
| 10 | `reflect.unsafe_NewArray` | 12.78GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.44GB | 1.44GB | 1.35GB | 512.14kB |
| `evaluation.mergeMetadata` | 757.18MB | 753.68MB | 710.61MB | 512.14kB |
| `local.(*Client).EvaluateV2` | 2.22GB | 2.21GB | 2.08GB | 512.14kB |
| `local.topologicalSort` | 319.46MB | 319.46MB | 300.64MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.11GB | 2.10GB | 1.97GB | 1.02MB |
| `localEvaluation.GetFeatureFlagPayload` | 321.17MB | 320.17MB | 310.29MB | 0B |
| `localEvaluation.getMapOfValue` | 2.11GB | 2.10GB | 1.97GB | 1.02MB |
| `utils.ParseFeatureFlag` | 2.11GB | 2.11GB | 1.97GB | 1.02MB |

**Total FF alloc (current snapshot):** 11.36GB  |  **24h avg:** 10.63GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.56MB | 71/3620 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.23MB | 96/3620 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3271/3620 | `██████████░░░░░ 72%` |
| 4 | `runtime.mallocgc` | 31.39MB | 3271/3620 | `█████████░░░░░░ 62%` |
| 5 | `database/sql.convertAssignRows` | 24.35MB | 121/3620 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3620 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 15.82MB | 2591/3620 | `████░░░░░░░░░░░ 31%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3620 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.54MB | 89/3620 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3620 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3620 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3620 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3620 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.96GB | 1923/3620 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 60.96GB | 2832/3620 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.71GB | 2994/3620 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.07GB | 2848/3620 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 51.8GB | 2612/3620 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3620 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.47GB | 2194/3620 | `█████░░░░░░░░░░ 38%` |

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
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
