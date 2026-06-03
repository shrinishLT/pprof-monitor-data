# Overview: prod
*Last updated: 2026-06-04 00:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:10 (957 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,705 | avg: 9,963 | max: 84,644 | trend: decreasing (-43.77/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇▆▇▇▆▆▆▆
```

**Heap InUse** (current: 139.1MB | avg: 146.8MB | max: 1896.6MB | trend: decreasing (-0.66MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁█▇▅▅▇▄▄▆▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,705 | 15,377 | -672 | 9,963 | 84,644 | decreasing (-43.77/hr) |
| Heap InUse | 139.1MB | 256.4MB | -117.3MB | 146.8MB | 1896.6MB | decreasing (-0.66MB/hr) |
| Heap Sys | 2432.1MB | 2430.9MB | +1.2MB | 2580.5MB | 6883.9MB | |
| Heap Objects | 374,412 | 1,557,752 | -1183340 | 627,671 | 8,100,802 | |

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
| 2026-06-04 | 3 | 14,734 | 183.8MB | 256.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.46MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `database/sql.convertAssignRows` | 4.0MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `bufio.NewWriterSize` | 3.02MB |
| 10 | `bytes.growSlice` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.56GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 1.39GB |
| 3 | `segmentio/kafka-go.makePartitions` | 843.55MB |
| 4 | `fmt.Sprintf` | 799.84MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 607.04MB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 589.01MB |
| 7 | `database/sql.convertAssignRows` | 495.02MB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 473.74MB |
| 9 | `reflect.unsafe_NewArray` | 443.38MB |
| 10 | `strconv.appendQuotedWith` | 375.75MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 54.53MB | 43.92MB | 86.15MB | 0B |
| `evaluation.mergeMetadata` | 30.51MB | 23.01MB | 43.06MB | 0B |
| `local.(*Client).EvaluateV2` | 80.75MB | 65.45MB | 131.41MB | 0B |
| `local.topologicalSort` | 15.21MB | 12.67MB | 21.29MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 69.63MB | 55.37MB | 110.33MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 16.24MB | 13.70MB | 31.22MB | 0B |
| `localEvaluation.getMapOfValue` | 69.63MB | 55.37MB | 110.33MB | 0B |
| `utils.ParseFeatureFlag` | 70.13MB | 55.87MB | 110.63MB | 0B |

**Total FF alloc (current snapshot):** 406.63MB  |  **24h avg:** 644.40MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/957 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/957 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 608/957 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.65MB | 33/957 | `████████░░░░░░░ 54%` |
| 5 | `runtime.mallocgc` | 22.14MB | 608/957 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.33MB | 421/957 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/957 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/957 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.68MB | 3/957 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 601/957 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/957 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/957 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/957 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/957 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.49GB | 585/957 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/957 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/957 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.25GB | 538/957 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 16.08GB | 275/957 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.84GB | 391/957 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (3.0x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.8x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.2x avg)
