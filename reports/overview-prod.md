# Overview: prod
*Last updated: 2026-06-04 04:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T04:00 (1003 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,997 | avg: 10,215 | max: 84,644 | trend: decreasing (-35.14/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅
```

**Heap InUse** (current: 203.0MB | avg: 152.5MB | max: 2823.8MB | trend: decreasing (-0.51MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,997 | 14,781 | +216 | 10,215 | 84,644 | decreasing (-35.14/hr) |
| Heap InUse | 203.0MB | 154.1MB | +48.9MB | 152.5MB | 2823.8MB | decreasing (-0.51MB/hr) |
| Heap Sys | 4528.0MB | 4529.0MB | -1.0MB | 2570.0MB | 6883.9MB | |
| Heap Objects | 756,430 | 280,530 | +475900 | 653,738 | 14,090,816 | |

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
| 2026-06-04 | 49 | 15,412 | 264.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.13MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bytes.growSlice` | 5.6MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 7 | `bufio.NewReaderSize` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.01MB |
| 10 | `crypto/tls.Client` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.38GB |
| 2 | `fmt.Sprintf` | 3.87GB |
| 3 | `jackskj/carta.getUniqueId` | 3.39GB |
| 4 | `reflect.growslice` | 3.39GB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.34GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 3.32GB |
| 7 | `reflect.unsafe_New` | 2.85GB |
| 8 | `fmt.(*buffer).writeString` | 2.1GB |
| 9 | `carta/value.NewCell` | 2.05GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.97GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 150.30MB | 146.29MB | 79.96MB | 0B |
| `evaluation.mergeMetadata` | 81.02MB | 78.02MB | 41.59MB | 0B |
| `local.(*Client).EvaluateV2` | 231.49MB | 224.84MB | 123.00MB | 0B |
| `local.topologicalSort` | 33.47MB | 32.96MB | 20.62MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 224.97MB | 218.82MB | 115.41MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 19.82MB | 19.32MB | 15.38MB | 0B |
| `localEvaluation.getMapOfValue` | 224.97MB | 218.82MB | 115.41MB | 0B |
| `utils.ParseFeatureFlag` | 224.97MB | 218.82MB | 115.55MB | 0B |

**Total FF alloc (current snapshot):** 1.16GB  |  **24h avg:** 626.93MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 67.61MB | 27/1003 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1003 | `█████████████░░ 93%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 654/1003 | `████████░░░░░░░ 54%` |
| 4 | `database/sql.convertAssignRows` | 33.77MB | 35/1003 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.51MB | 654/1003 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1003 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 13.18MB | 461/1003 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 11.31MB | 8/1003 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 17/1003 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1003 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1003 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1003 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1003 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1003 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 44.34GB | 631/1003 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1003 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1003 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.04GB | 574/1003 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 14.05GB | 321/1003 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.58GB | 436/1003 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.3x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
