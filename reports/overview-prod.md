# Overview: prod
*Last updated: 2026-06-13 04:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T04:16 (3596 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,563 | avg: 14,526 | max: 84,644 | trend: INCREASING (+3.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▅▃▄▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▃▂▂▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 313.8MB | avg: 239.5MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▅▃▃▄▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▄▃▃▃▄▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▃▄▄▂▃▂▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,563 | 14,997 | +1566 | 14,526 | 84,644 | INCREASING (+3.35/hr) |
| Heap InUse | 313.8MB | 201.9MB | +111.9MB | 239.5MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1403.3MB | 1406.1MB | -2.8MB | 2584.5MB | 6883.9MB | |
| Heap Objects | 1,493,942 | 890,588 | +603354 | 1,029,559 | 17,165,538 | |

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
| 2026-06-13 | 52 | 18,117 | 306.1MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 23.22MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 4 | `bytes.growSlice` | 11.06MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `bufio.NewReaderSize` | 6.04MB |
| 8 | `bufio.NewWriterSize` | 4.53MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 22.31GB |
| 2 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 15.53GB |
| 3 | `fmt.Sprintf` | 15.15GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 12.82GB |
| 5 | `jackskj/carta.getUniqueId` | 12.34GB |
| 6 | `reflect.growslice` | 12.3GB |
| 7 | `reflect.unsafe_NewArray` | 11.36GB |
| 8 | `reflect.unsafe_New` | 10.89GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 9.32GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 7.87GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.36GB | 1.35GB | 1.24GB | 0B |
| `evaluation.mergeMetadata` | 712.67MB | 707.67MB | 650.39MB | 0B |
| `local.(*Client).EvaluateV2` | 2.09GB | 2.08GB | 1.91GB | 0B |
| `local.topologicalSort` | 302.25MB | 300.73MB | 276.03MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.98GB | 1.96GB | 1.79GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 310.41MB | 310.41MB | 293.08MB | 0B |
| `localEvaluation.getMapOfValue` | 1.98GB | 1.96GB | 1.79GB | 0B |
| `utils.ParseFeatureFlag` | 1.98GB | 1.97GB | 1.79GB | 0B |

**Total FF alloc (current snapshot):** 10.68GB  |  **24h avg:** 9.71GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.56MB | 71/3596 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.23MB | 96/3596 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3247/3596 | `██████████░░░░░ 72%` |
| 4 | `runtime.mallocgc` | 31.45MB | 3247/3596 | `█████████░░░░░░ 62%` |
| 5 | `database/sql.convertAssignRows` | 24.35MB | 121/3596 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3596 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 15.87MB | 2571/3596 | `████░░░░░░░░░░░ 31%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3596 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.54MB | 89/3596 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3596 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3596 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3596 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3596 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3596 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 61.33GB | 2808/3596 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.01GB | 2970/3596 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.4GB | 2824/3596 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 52.15GB | 2588/3596 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3596 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3596 | `█████░░░░░░░░░░ 38%` |

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
