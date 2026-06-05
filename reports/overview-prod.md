# Overview: prod
*Last updated: 2026-06-05 08:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T08:15 (1342 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,054 | avg: 11,732 | max: 84,644 | trend: decreasing (-4.83/hr))
```
▁▁▁▁▂▇▄▁▁▂▁▁▁▁▁▂▃▂▃▃▃▂▂▁▂▄▂▁▂▃▁▁▁▃▁▂▁▂▂▃▄▃▄▆▆▁▁▁▁▁▁▂▂▁▇▃▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 344.5MB | avg: 179.9MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,054 | 14,610 | +3444 | 11,732 | 84,644 | decreasing (-4.83/hr) |
| Heap InUse | 344.5MB | 147.1MB | +197.4MB | 179.9MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 1000.5MB | 1016.6MB | -16.1MB | 2688.9MB | 6883.9MB | |
| Heap Objects | 1,842,077 | 690,617 | +1151460 | 801,919 | 17,165,538 | |

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
| 2026-06-05 | 100 | 14,857 | 249.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 22.11MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 4 | `runtime.mallocgc` | 11.51MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 8.53MB |
| 7 | `bufio.NewWriterSize` | 6.02MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.22GB |
| 2 | `segmentio/kafka-go.makePartitions` | 1.79GB |
| 3 | `reflect.unsafe_NewArray` | 893.92MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 888.91MB |
| 5 | `reflect.MakeSlice` | 532.01MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 516.45MB |
| 7 | `jackskj/carta.getUniqueId` | 502.6MB |
| 8 | `fmt.Sprintf` | 447.59MB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 425.45MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 420.51MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 106.65MB | 97.02MB | 165.30MB | 0B |
| `evaluation.mergeMetadata` | 56.01MB | 51.51MB | 83.67MB | 0B |
| `local.(*Client).EvaluateV2` | 155.64MB | 143.42MB | 249.38MB | 0B |
| `local.topologicalSort` | 21.75MB | 20.22MB | 36.47MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 159.15MB | 145.90MB | 248.37MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 13.39MB | 13.39MB | 25.43MB | 0B |
| `localEvaluation.getMapOfValue` | 159.15MB | 145.90MB | 248.37MB | 0B |
| `utils.ParseFeatureFlag` | 159.15MB | 145.90MB | 249.02MB | 0B |

**Total FF alloc (current snapshot):** 830.89MB  |  **24h avg:** 1.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1342 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1342 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1342 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 993/1342 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.09MB | 993/1342 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1342 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.22MB | 758/1342 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1342 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1342 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1342 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1342 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1342 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1342 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1342 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1342 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.78GB | 964/1342 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1342 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.43GB | 887/1342 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.76GB | 544/1342 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.58GB | 187/1342 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
