# Overview: prod
*Last updated: 2026-06-08 09:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T09:15 (2217 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,680 | avg: 13,293 | max: 84,644 | trend: INCREASING (+3.66/hr))
```
▃▁▁▂▁▁▂▄▄▃▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▂▂▁▃▆▅▄▁▁▁▁▁▃▂▂▃▃▂▄▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▃▂▂▁▁▂▂▁▂
```

**Heap InUse** (current: 296.5MB | avg: 199.9MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▄▂▂▃▂▁▃▆▅▃▄▇▁▄▄▅▅▂▅▁▃▂▂▂▃▅▄▂▅▄▃▂▅▃▄▅▁▂▂▄▃▁▃▄▃▅▅▅▅▅▆█▄▁▂▄▁▆▃▄▄▄▄▄▄▂▁▃▂▃▃▃▂▄▂▄▄▃▄▆▄▁▂▃▅▆▆▅▆▃▂▃▃▅▁▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,680 | 14,343 | +337 | 13,293 | 84,644 | INCREASING (+3.66/hr) |
| Heap InUse | 296.5MB | 190.2MB | +106.3MB | 199.9MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3219.7MB | 3219.8MB | -0.1MB | 2349.3MB | 6883.9MB | |
| Heap Objects | 1,506,976 | 515,058 | +991918 | 898,543 | 17,165,538 | |

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
| 2026-06-08 | 112 | 14,507 | 239.0MB | 333.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.56MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `bytes.growSlice` | 3.01MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 60.07GB |
| 2 | `reflect.growslice` | 48.91GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 48.3GB |
| 4 | `jackskj/carta.getUniqueId` | 40.96GB |
| 5 | `reflect.unsafe_New` | 37.22GB |
| 6 | `fmt.(*buffer).writeString` | 30.92GB |
| 7 | `reflect.unsafe_NewArray` | 30.72GB |
| 8 | `carta/value.NewCell` | 26.49GB |
| 9 | `fmt.Sprintf` | 21.96GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.71GB | 1.71GB | 1.58GB | 0B |
| `evaluation.mergeMetadata` | 907.22MB | 905.72MB | 835.49MB | 0B |
| `local.(*Client).EvaluateV2` | 2.60GB | 2.59GB | 2.39GB | 0B |
| `local.topologicalSort` | 356.91MB | 355.90MB | 326.10MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.61GB | 2.60GB | 2.39GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 255.57MB | 255.57MB | 245.98MB | 0B |
| `localEvaluation.getMapOfValue` | 2.61GB | 2.60GB | 2.39GB | 0B |
| `utils.ParseFeatureFlag` | 2.61GB | 2.61GB | 2.39GB | 0B |

**Total FF alloc (current snapshot):** 13.63GB  |  **24h avg:** 12.52GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2217 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2217 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1868/2217 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2217 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.44MB | 1868/2217 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2217 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.23MB | 1352/2217 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2217 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2217 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2217 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2217 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2217 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2217 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2217 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2217 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2217 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2217 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 22.63GB | 734/2217 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `segmentio/kafka-go.makePartitions` | 17.57GB | 1591/2217 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.growslice` | 15.41GB | 1429/2217 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
