# Overview: prod
*Last updated: 2026-06-16 01:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T01:10 (4421 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,108 | avg: 14,797 | max: 84,644 | trend: INCREASING (+2.40/hr))
```
▃▂▂▂▂▂▂▁▁▁▁▂▅▃▁▂▂▃▄▂▃▂▃▃▃▁▃▁▇▃▃▁▁▂▃▄▄▂▄▂▃▂▂▂▂▆▄▃▁▁▁▁▃▆▄▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▄▆▂▂▃▁▁▁▄▁▁▂▅▃▁▄▇▂▁█▄▃▂▄
```

**Heap InUse** (current: 376.7MB | avg: 245.1MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▃▂▃▂▂▃▃▂▂▂▃▂▆▄▂▂▃▃▃▂▄▄▆▃▄▁▄▂▆▃▃▂▁▂▄▅▄▂▅▂▃▂▃▃▃▅▄▃▂▁▂▁▃▇▄▄▃▃▃▂▃▂▂▄▁▂▃▂▂▂▂▂▃█▂▂▄▁▁▁▃▂▂▃▄▄▂▄▆▂▃▆▅▂▃▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,108 | 15,339 | +2769 | 14,797 | 84,644 | INCREASING (+2.40/hr) |
| Heap InUse | 376.7MB | 280.2MB | +96.5MB | 245.1MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2419.3MB | 2419.9MB | -0.6MB | 2522.2MB | 6883.9MB | |
| Heap Objects | 1,577,323 | 1,597,518 | -20195 | 1,049,677 | 17,165,538 | |

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
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 15 | 16,871 | 318.8MB | 455.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 20.61MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.07MB |
| 5 | `bufio.NewReaderSize` | 14.05MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewWriterSize` | 8.55MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.5MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 116.6GB |
| 2 | `reflect.growslice` | 110.85GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.87GB |
| 4 | `jackskj/carta.getUniqueId` | 101.1GB |
| 5 | `reflect.unsafe_New` | 88.25GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 83.66GB |
| 7 | `fmt.Sprintf` | 82.2GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 68.83GB |
| 9 | `fmt.(*buffer).writeString` | 68.49GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 64.54GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.21GB | 5.20GB | 5.05GB | 0B |
| `evaluation.mergeMetadata` | 2.71GB | 2.70GB | 2.62GB | 0B |
| `local.(*Client).EvaluateV2` | 8.01GB | 8.00GB | 7.75GB | 0B |
| `local.topologicalSort` | 1.13GB | 1.13GB | 1.09GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.75GB | 7.74GB | 7.51GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.02GB | 1.02GB | 1011.13MB | 0B |
| `localEvaluation.getMapOfValue` | 7.75GB | 7.74GB | 7.51GB | 0B |
| `utils.ParseFeatureFlag` | 7.76GB | 7.75GB | 7.52GB | 0B |

**Total FF alloc (current snapshot):** 41.32GB  |  **24h avg:** 40.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.36MB | 90/4421 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.02MB | 123/4421 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4072/4421 | `████████████░░░ 86%` |
| 4 | `runtime.mallocgc` | 31.35MB | 4072/4421 | `███████████░░░░ 74%` |
| 5 | `database/sql.convertAssignRows` | 21.51MB | 145/4421 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4421 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.82MB | 3189/4421 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.21MB | 119/4421 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4421 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4421 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4421 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4421 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4421 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 74.06GB | 2610/4421 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.07GB | 3633/4421 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.84GB | 3795/4421 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.3GB | 3649/4421 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 52.84GB | 3413/4421 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4421 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.34GB | 2967/4421 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
