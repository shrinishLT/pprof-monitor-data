# Overview: prod
*Last updated: 2026-06-05 01:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T01:35 (1262 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,210 | avg: 11,532 | max: 84,644 | trend: decreasing (-7.83/hr))
```
▁▂▂▂▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 177.0MB | avg: 176.8MB | max: 3154.1MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,210 | 14,695 | +515 | 11,532 | 84,644 | decreasing (-7.83/hr) |
| Heap InUse | 177.0MB | 152.8MB | +24.2MB | 176.8MB | 3154.1MB | stable (-0.07MB/hr) |
| Heap Sys | 4655.6MB | 4655.3MB | +0.3MB | 2661.7MB | 6883.9MB | |
| Heap Objects | 762,736 | 425,155 | +337581 | 773,732 | 17,165,538 | |

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
| 2026-06-05 | 20 | 14,736 | 335.6MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 9.05MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 8 | `reflect.growslice` | 3.33MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 16.51GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.57GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.45GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.39GB |
| 5 | `database/sql.convertAssignRows` | 2.06GB |
| 6 | `reflect.unsafe_NewArray` | 1.79GB |
| 7 | `fmt.Sprintf` | 1.7GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.51GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.25GB |
| 10 | `jackskj/carta.getUniqueId` | 1.14GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 224.00MB | 218.98MB | 267.70MB | 0B |
| `evaluation.mergeMetadata` | 111.03MB | 107.53MB | 138.81MB | 0B |
| `local.(*Client).EvaluateV2` | 324.74MB | 316.60MB | 404.78MB | 0B |
| `local.topologicalSort` | 48.59MB | 47.58MB | 55.96MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 304.29MB | 295.14MB | 359.16MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 44.51MB | 44.51MB | 79.35MB | 0B |
| `localEvaluation.getMapOfValue` | 304.29MB | 295.14MB | 359.16MB | 0B |
| `utils.ParseFeatureFlag` | 304.29MB | 295.14MB | 359.32MB | 0B |

**Total FF alloc (current snapshot):** 1.63GB  |  **24h avg:** 1.98GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.25MB | 26/1262 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.68MB | 42/1262 | `██████████████░ 95%` |
| 3 | `database/sql.convertAssignRows` | 37.1MB | 54/1262 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 913/1262 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 18.95MB | 913/1262 | `███░░░░░░░░░░░░ 23%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1262 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 14.94MB | 691/1262 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1262 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1262 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1262 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1262 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1262 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1262 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1262 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1262 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 36.59GB | 885/1262 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1262 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.37GB | 808/1262 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 10.49GB | 500/1262 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1262 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.5x avg)
