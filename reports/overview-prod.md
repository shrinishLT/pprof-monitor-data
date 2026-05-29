# Overview: prod
*Last updated: 2026-05-29 15:24 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T15:23 (691 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,128 | avg: 13,571 | max: 84,644 | trend: decreasing (-30.97/hr))
```
▆▇▆▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 333.9MB | avg: 200.2MB | max: 1896.6MB | trend: stable (-0.48MB/hr))
```
▄▅▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,128 | 0 | +18128 | 13,571 | 84,644 | decreasing (-30.97/hr) |
| Heap InUse | 333.9MB | 0.0MB | +333.9MB | 200.2MB | 1896.6MB | stable (-0.48MB/hr) |
| Heap Sys | 3564.0MB | 0.0MB | +3564.0MB | 3536.6MB | 6883.9MB | |
| Heap Objects | 1,619,045 | 0 | +1619045 | 856,990 | 8,100,802 | |

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
| 2026-05-29 | 32 | 566 | 10.4MB | 333.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 25.63MB |
| 3 | `runtime.mallocgc` | 16.11MB |
| 4 | `bufio.NewWriterSize` | 13.55MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 6 | `bufio.NewReaderSize` | 10.04MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).dialConn` | 4.5MB |
| 10 | `compress/flate.NewWriter` | 4.41MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 11.94GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 4.69GB |
| 3 | `segmentio/kafka-go.makePartitions` | 2.71GB |
| 4 | `fmt.Sprintf` | 2.34GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.83GB |
| 6 | `reflect.growslice` | 1.68GB |
| 7 | `jackskj/carta.getUniqueId` | 1.64GB |
| 8 | `database/sql.convertAssignRows` | 1.54GB |
| 9 | `reflect.unsafe_NewArray` | 1.42GB |
| 10 | `reflect.unsafe_New` | 1.33GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 237.61MB | 0B | 237.61MB | 0B |
| `evaluation.mergeMetadata` | 122.53MB | 0B | 122.53MB | 0B |
| `local.(*Client).EvaluateV2` | 362.49MB | 0B | 362.49MB | 0B |
| `local.topologicalSort` | 49.71MB | 0B | 49.71MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 338.58MB | 0B | 338.58MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 56.22MB | 0B | 56.22MB | 0B |
| `localEvaluation.getMapOfValue` | 338.58MB | 0B | 338.58MB | 0B |
| `utils.ParseFeatureFlag` | 338.58MB | 0B | 338.58MB | 0B |

**Total FF alloc (current snapshot):** 1.80GB  |  **24h avg:** 1.80GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/691 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/691 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 598/691 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.36MB | 32/691 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.32MB | 598/691 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.29MB | 412/691 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/691 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/691 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/691 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 591/691 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/691 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/691 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/691 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/691 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.24GB | 575/691 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/691 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/691 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.62GB | 528/691 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 16.64GB | 265/691 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.17GB | 381/691 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (5.0x avg)
