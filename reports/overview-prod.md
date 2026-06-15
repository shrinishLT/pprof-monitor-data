# Overview: prod
*Last updated: 2026-06-15 19:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T19:06 (4350 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,515 | avg: 14,775 | max: 84,644 | trend: INCREASING (+2.46/hr))
```
▁▁▁▁▂▃▂▂▁▁▁▂▂▄▁▁▁▅▅▄▃▅▄▄▂▁▁▁▁▃▄▁▁▁▃▃▁▁▁▁▁▂▂▁▁▁▁▃▂▅▂▁▁▂▇▇▇▄▄█▂▂▂▃▂▂▁▁▁▃▂▃▂▂▂▂▂▂▁▁▁▁▂▆▄▁▂▂▃▄▂▃▂▄▃▃
```

**Heap InUse** (current: 339.7MB | avg: 244.3MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▂▃▂▃▃▃▂▂▁▁▃▃▄▂▁▁▄▄▃▃▃▅▅▂▂▁▁▁▃▃▁▂▁▄▄▃▃▁▁▂▂▃▂▃▂▂▂▃▄▃▂▂▂▅▇█▅▅▆▃▂▂▂▃▃▃▁▁▃▂▃▂▂▂▂▃▃▂▂▁▃▂▆▅▂▂▃▃▄▂▄▄▆▃▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,515 | 16,206 | +309 | 14,775 | 84,644 | INCREASING (+2.46/hr) |
| Heap InUse | 339.7MB | 289.9MB | +49.8MB | 244.3MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2429.1MB | 2432.1MB | -3.0MB | 2523.8MB | 6883.9MB | |
| Heap Objects | 1,791,245 | 1,138,331 | +652914 | 1,047,742 | 17,165,538 | |

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
| 2026-06-15 | 230 | 16,185 | 280.3MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 20.53MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 8.53MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `bufio.NewWriterSize` | 5.55MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 109.98GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.67GB |
| 3 | `segmentio/kafka-go.makePartitions` | 108.25GB |
| 4 | `jackskj/carta.getUniqueId` | 99.83GB |
| 5 | `reflect.unsafe_New` | 87.33GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 79.51GB |
| 7 | `fmt.Sprintf` | 74.41GB |
| 8 | `fmt.(*buffer).writeString` | 68.06GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 65.43GB |
| 10 | `carta/value.NewCell` | 63.17GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.57GB | 4.55GB | 4.30GB | 0B |
| `evaluation.mergeMetadata` | 2.37GB | 2.36GB | 2.23GB | 0B |
| `local.(*Client).EvaluateV2` | 7.02GB | 6.99GB | 6.62GB | 0B |
| `local.topologicalSort` | 1020.96MB | 1018.42MB | 960.27MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.83GB | 6.80GB | 6.46GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 890.07MB | 886.93MB | 816.95MB | 0B |
| `localEvaluation.getMapOfValue` | 6.83GB | 6.80GB | 6.46GB | 0B |
| `utils.ParseFeatureFlag` | 6.84GB | 6.81GB | 6.47GB | 0B |

**Total FF alloc (current snapshot):** 36.32GB  |  **24h avg:** 34.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.12MB | 88/4350 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.23MB | 122/4350 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4001/4350 | `████████████░░░ 84%` |
| 4 | `runtime.mallocgc` | 31.33MB | 4001/4350 | `██████████░░░░░ 72%` |
| 5 | `database/sql.convertAssignRows` | 21.72MB | 143/4350 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4350 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.83MB | 3123/4350 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.35MB | 117/4350 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4350 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4350 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4350 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4350 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4350 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.06GB | 2539/4350 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 62.13GB | 3562/4350 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.89GB | 3724/4350 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.42GB | 3578/4350 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 52.1GB | 3342/4350 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4350 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.83GB | 2896/4350 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
