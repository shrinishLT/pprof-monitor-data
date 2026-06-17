# Overview: prod
*Last updated: 2026-06-17 17:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T17:41 (4905 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,817 | avg: 14,949 | max: 84,644 | trend: INCREASING (+2.10/hr))
```
▁▁▁▁▂▃▄▄▃▅▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 249.9MB | avg: 246.1MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▁▃▄▅▄▄▆█▇▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,817 | 15,563 | +254 | 14,949 | 84,644 | INCREASING (+2.10/hr) |
| Heap InUse | 249.9MB | 215.1MB | +34.8MB | 246.1MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2236.6MB | 2227.5MB | +9.1MB | 2420.7MB | 6883.9MB | |
| Heap Objects | 873,835 | 866,912 | +6923 | 1,055,459 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 213 | 16,620 | 262.5MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `bytes.growSlice` | 12.19MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 7.54MB |
| 6 | `bufio.NewWriterSize` | 6.05MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 41.49GB |
| 2 | `reflect.growslice` | 40.69GB |
| 3 | `jackskj/carta.getUniqueId` | 37.93GB |
| 4 | `reflect.unsafe_New` | 33.16GB |
| 5 | `fmt.Sprintf` | 31.71GB |
| 6 | `fmt.(*buffer).writeString` | 25.04GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 24.79GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 24.31GB |
| 9 | `carta/value.NewCell` | 23.35GB |
| 10 | `reflect.unsafe_NewArray` | 21.43GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.74GB | 2.73GB | 2.52GB | 0B |
| `evaluation.mergeMetadata` | 1.40GB | 1.39GB | 1.29GB | 0B |
| `local.(*Client).EvaluateV2` | 4.17GB | 4.16GB | 3.84GB | 0B |
| `local.topologicalSort` | 583.04MB | 581.00MB | 537.25MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.00GB | 4.00GB | 3.70GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 574.13MB | 571.58MB | 513.89MB | 0B |
| `localEvaluation.getMapOfValue` | 4.00GB | 4.00GB | 3.70GB | 0B |
| `utils.ParseFeatureFlag` | 4.01GB | 4.01GB | 3.71GB | 0B |

**Total FF alloc (current snapshot):** 21.46GB  |  **24h avg:** 19.79GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.54MB | 104/4905 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4556/4905 | `██████████████░ 97%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.61MB | 139/4905 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4556/4905 | `████████████░░░ 80%` |
| 5 | `database/sql.convertAssignRows` | 19.76MB | 163/4905 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4905 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.78MB | 3624/4905 | `██████░░░░░░░░░ 42%` |
| 8 | `net/http.(*Transport).dialConn` | 13.27MB | 138/4905 | `█████░░░░░░░░░░ 35%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4905 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4905 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4905 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4905 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4905 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 74.21GB | 2822/4905 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 60.99GB | 4279/4905 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.73GB | 4117/4905 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.33GB | 4133/4905 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4905 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.57GB | 3897/4905 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.13GB | 3308/4905 | `█████░░░░░░░░░░ 36%` |

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
