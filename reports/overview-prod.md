# Overview: prod
*Last updated: 2026-06-16 12:53 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T12:53 (4560 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,336 | avg: 14,855 | max: 84,644 | trend: INCREASING (+2.34/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▃▄▄▅▆█▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 203.8MB | avg: 246.2MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▅▃▄▅▅▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,336 | 15,995 | -659 | 14,855 | 84,644 | INCREASING (+2.34/hr) |
| Heap InUse | 203.8MB | 237.6MB | -33.8MB | 246.2MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 321.6MB | 321.5MB | +0.1MB | 2510.9MB | 6883.9MB | |
| Heap Objects | 727,301 | 894,545 | -167244 | 1,054,399 | 17,165,538 | |

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
| 2026-06-16 | 154 | 16,731 | 284.9MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `bytes.growSlice` | 9.35MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 5.03MB |
| 6 | `bufio.NewReaderSize` | 4.52MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 3.26GB |
| 2 | `jackskj/carta.getUniqueId` | 3.01GB |
| 3 | `reflect.unsafe_New` | 2.73GB |
| 4 | `segmentio/kafka-go.makePartitions` | 2.0GB |
| 5 | `fmt.(*buffer).writeString` | 1.95GB |
| 6 | `carta/value.NewCell` | 1.85GB |
| 7 | `fmt.Sprintf` | 1.75GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.73GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.43GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.32GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 129.87MB | 121.26MB | 3.71GB | 0B |
| `evaluation.mergeMetadata` | 71.02MB | 67.02MB | 1.92GB | 0B |
| `local.(*Client).EvaluateV2` | 198.99MB | 183.22MB | 5.69GB | 0B |
| `local.topologicalSort` | 27.25MB | 24.22MB | 822.51MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 198.09MB | 181.27MB | 5.52GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 23.94MB | 22.43MB | 723.09MB | 0B |
| `localEvaluation.getMapOfValue` | 198.09MB | 181.27MB | 5.52GB | 0B |
| `utils.ParseFeatureFlag` | 198.09MB | 181.27MB | 5.53GB | 0B |

**Total FF alloc (current snapshot):** 1.02GB  |  **24h avg:** 29.41GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 40.18MB | 96/4560 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4211/4560 | `█████████████░░ 91%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 36.19MB | 130/4560 | `█████████████░░ 90%` |
| 4 | `runtime.mallocgc` | 31.29MB | 4211/4560 | `███████████░░░░ 77%` |
| 5 | `database/sql.convertAssignRows` | 20.72MB | 152/4560 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4560 | `██████░░░░░░░░░ 44%` |
| 7 | `bytes.growSlice` | 15.88MB | 3312/4560 | `█████░░░░░░░░░░ 39%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4560 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4560 | `████░░░░░░░░░░░ 29%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4560 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4560 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.9GB | 2732/4560 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4560 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4560 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.65GB | 3772/4560 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.43GB | 3934/4560 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.75GB | 3788/4560 | `██████░░░░░░░░░ 46%` |
| 8 | `reflect.unsafe_New` | 54.06GB | 3552/4560 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4560 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.15GB | 3106/4560 | `█████░░░░░░░░░░ 38%` |

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
