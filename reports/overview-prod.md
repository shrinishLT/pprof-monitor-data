# Overview: prod
*Last updated: 2026-06-04 16:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T16:40 (1155 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,299 | avg: 11,164 | max: 84,644 | trend: decreasing (-14.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 468.9MB | avg: 170.0MB | max: 2823.8MB | trend: stable (-0.17MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁▁▁▁▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,299 | 17,506 | +793 | 11,164 | 84,644 | decreasing (-14.38/hr) |
| Heap InUse | 468.9MB | 308.4MB | +160.5MB | 170.0MB | 2823.8MB | stable (-0.17MB/hr) |
| Heap Sys | 4155.5MB | 4153.7MB | +1.8MB | 2657.9MB | 6883.9MB | |
| Heap Objects | 4,542,121 | 1,395,958 | +3146163 | 734,793 | 14,090,816 | |

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
| 2026-06-04 | 201 | 16,932 | 280.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 123.19MB |
| 2 | `database/sql.convertAssignRows` | 54.5MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bytes.growSlice` | 26.66MB |
| 5 | `bufio.NewReaderSize` | 12.55MB |
| 6 | `runtime.mallocgc` | 11.51MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.71MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.04MB |
| 10 | `bufio.NewWriterSize` | 8.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 22.14GB |
| 2 | `fmt.Sprintf` | 10.29GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 8.9GB |
| 4 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 8.61GB |
| 5 | `segmentio/kafka-go.makePartitions` | 7.05GB |
| 6 | `reflect.growslice` | 6.39GB |
| 7 | `jackskj/carta.getUniqueId` | 6.31GB |
| 8 | `reflect.unsafe_New` | 5.33GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.15GB |
| 10 | `fmt.Sprint` | 5.0GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 659.55MB | 651.95MB | 401.27MB | 0B |
| `evaluation.mergeMetadata` | 339.58MB | 335.58MB | 208.73MB | 0B |
| `local.(*Client).EvaluateV2` | 1.00GB | 1011.26MB | 615.13MB | 0B |
| `local.topologicalSort` | 145.74MB | 142.70MB | 86.27MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 947.50MB | 935.70MB | 572.66MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 161.07MB | 158.52MB | 97.07MB | 0B |
| `localEvaluation.getMapOfValue` | 947.50MB | 935.70MB | 572.66MB | 0B |
| `utils.ParseFeatureFlag` | 947.50MB | 935.70MB | 572.66MB | 0B |

**Total FF alloc (current snapshot):** 5.05GB  |  **24h avg:** 3.05GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1155 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1155 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 806/1155 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 32.21MB | 50/1155 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 20.01MB | 806/1155 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1155 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.55MB | 593/1155 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1155 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1155 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1155 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1155 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1155 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1155 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1155 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1155 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.46GB | 779/1155 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1155 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.32GB | 703/1155 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.35GB | 398/1155 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.01GB | 540/1155 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
