# Overview: prod
*Last updated: 2026-06-14 02:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T02:35 (3864 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,769 | avg: 14,622 | max: 84,644 | trend: INCREASING (+2.97/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆█▅▃▄▃▄▅▅▃▃▃▃▄▄▃▄▃▄▃▃▂▂▂▃▃▂▂▃▃▃▃▄▃▃▃▃▃▃▃▄▄▃▄▃▄▄▄▄▄▃▄▃▃▃▃
```

**Heap InUse** (current: 264.2MB | avg: 240.9MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▂▂▁▂▁▃▃▁▂▄▂▁▁▂▂▁▂▂▂▁▁▂▂▁▃▂▃▁▁▃▁▂▃▂▂▃▁▁▁▁▆█▄▃▄▃▄▃▄▄▃▄▃▄▅▃▄▃▄▃▃▂▂▃▃▅▂▂▃▃▄▃▅▄▂▅▄▃▃▅▃▄▄▅▅▃▄▄▃▄▄▄▅▃▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,769 | 16,286 | -517 | 14,622 | 84,644 | INCREASING (+2.97/hr) |
| Heap InUse | 264.2MB | 255.5MB | +8.7MB | 240.9MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2297.8MB | 2297.7MB | +0.1MB | 2542.9MB | 6883.9MB | |
| Heap Objects | 966,092 | 844,221 | +121871 | 1,036,735 | 17,165,538 | |

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
| 2026-06-14 | 32 | 16,181 | 291.3MB | 371.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `bytes.growSlice` | 17.66MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewReaderSize` | 4.01MB |
| 7 | `bufio.NewWriterSize` | 3.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 52.83GB |
| 2 | `reflect.growslice` | 46.39GB |
| 3 | `jackskj/carta.getUniqueId` | 43.67GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 39.52GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 38.97GB |
| 6 | `reflect.unsafe_New` | 37.95GB |
| 7 | `fmt.Sprintf` | 37.37GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 32.07GB |
| 9 | `fmt.(*buffer).writeString` | 28.68GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 27.78GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.26GB | 2.25GB | 2.15GB | 0B |
| `evaluation.mergeMetadata` | 1.16GB | 1.16GB | 1.11GB | 0B |
| `local.(*Client).EvaluateV2` | 3.47GB | 3.46GB | 3.31GB | 0B |
| `local.topologicalSort` | 504.83MB | 504.32MB | 477.68MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.38GB | 3.38GB | 3.22GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 422.73MB | 422.73MB | 412.77MB | 0B |
| `localEvaluation.getMapOfValue` | 3.38GB | 3.38GB | 3.22GB | 0B |
| `utils.ParseFeatureFlag` | 3.39GB | 3.38GB | 3.23GB | 0B |

**Total FF alloc (current snapshot):** 17.95GB  |  **24h avg:** 17.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.23MB | 75/3864 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.26MB | 106/3864 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3515/3864 | `███████████░░░░ 75%` |
| 4 | `runtime.mallocgc` | 31.23MB | 3515/3864 | `█████████░░░░░░ 64%` |
| 5 | `database/sql.convertAssignRows` | 23.55MB | 126/3864 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3864 | `█████░░░░░░░░░░ 37%` |
| 7 | `bytes.growSlice` | 15.78MB | 2770/3864 | `████░░░░░░░░░░░ 32%` |
| 8 | `net/http.(*Transport).dialConn` | 13.23MB | 101/3864 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3864 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3864 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3864 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3864 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3864 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.93GB | 2053/3864 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.07GB | 3238/3864 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 59.02GB | 3076/3864 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.41GB | 3092/3864 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3864 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.89GB | 2856/3864 | `█████░░░░░░░░░░ 39%` |
| 10 | `fmt.(*buffer).writeString` | 46.03GB | 2410/3864 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
