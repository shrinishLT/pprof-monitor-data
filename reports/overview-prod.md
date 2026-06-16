# Overview: prod
*Last updated: 2026-06-16 06:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T06:05 (4480 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,005 | avg: 14,800 | max: 84,644 | trend: INCREASING (+2.32/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▂▁▄▆▂▂▃▁▁▁▄▁▁▂▅▃▁▄▇▂▁█▄▃▂▄▂▁▁▁▃▁▁▁▃▂▂▁▁▁▁▃▃▁▂▁▁▄▄▁▁▁▁▁▂▁▁▁▁▃▂▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁
```

**Heap InUse** (current: 294.2MB | avg: 245.1MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▃▂▂▄▁▂▃▂▂▂▂▂▃█▂▂▄▁▁▁▃▂▂▃▄▄▂▄▆▂▃▆▅▂▃▅▃▁▂▂▂▃▁▂▂▂▂▁▁▃▂▃▄▂▂▂▂▄▅▂▂▂▁▂▃▁▁▂▃▃▂▃▁▁▁▃▂▁▂▂▁▂▃▂▂▂▃▂▃▁▂▁▁▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,005 | 14,417 | +588 | 14,800 | 84,644 | INCREASING (+2.32/hr) |
| Heap InUse | 294.2MB | 215.6MB | +78.6MB | 245.1MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2432.6MB | 2432.9MB | -0.3MB | 2521.0MB | 6883.9MB | |
| Heap Objects | 1,680,702 | 901,411 | +779291 | 1,049,533 | 17,165,538 | |

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
| 2026-06-16 | 74 | 15,415 | 261.4MB | 455.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 11.08MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `compress/flate.NewWriter` | 6.17MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `bufio.NewWriterSize` | 3.03MB |
| 9 | `bufio.NewReaderSize` | 3.01MB |
| 10 | `reflect.unsafe_NewArray` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 124.48GB |
| 2 | `segmentio/kafka-go.makePartitions` | 123.32GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 117.95GB |
| 4 | `jackskj/carta.getUniqueId` | 111.71GB |
| 5 | `reflect.unsafe_New` | 98.25GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 89.55GB |
| 7 | `fmt.Sprintf` | 87.67GB |
| 8 | `fmt.(*buffer).writeString` | 76.95GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 73.65GB |
| 10 | `carta/value.NewCell` | 70.92GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.55GB | 5.54GB | 5.42GB | 0B |
| `evaluation.mergeMetadata` | 2.88GB | 2.87GB | 2.81GB | 0B |
| `local.(*Client).EvaluateV2` | 8.54GB | 8.53GB | 8.33GB | 0B |
| `local.topologicalSort` | 1.21GB | 1.21GB | 1.18GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.27GB | 8.26GB | 8.07GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.07GB | 1.07GB | 1.05GB | 0B |
| `localEvaluation.getMapOfValue` | 8.27GB | 8.26GB | 8.07GB | 0B |
| `utils.ParseFeatureFlag` | 8.29GB | 8.28GB | 8.08GB | 0B |

**Total FF alloc (current snapshot):** 44.06GB  |  **24h avg:** 43.01GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 41.59MB | 92/4480 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 37.49MB | 125/4480 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4131/4480 | `█████████████░░ 88%` |
| 4 | `runtime.mallocgc` | 31.37MB | 4131/4480 | `███████████░░░░ 75%` |
| 5 | `database/sql.convertAssignRows` | 21.27MB | 147/4480 | `███████░░░░░░░░ 51%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4480 | `██████░░░░░░░░░ 43%` |
| 7 | `bytes.growSlice` | 15.68MB | 3244/4480 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.21MB | 119/4480 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4480 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4480 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4480 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 74.9GB | 2669/4480 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4480 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4480 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.9GB | 3692/4480 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.72GB | 3854/4480 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 57.07GB | 3708/4480 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.49GB | 3472/4480 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4480 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.8GB | 3026/4480 | `█████░░░░░░░░░░ 38%` |

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
