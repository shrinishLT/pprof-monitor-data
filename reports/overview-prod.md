# Overview: prod
*Last updated: 2026-06-05 06:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T06:20 (1319 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,835 | avg: 11,683 | max: 84,644 | trend: decreasing (-5.54/hr))
```
▁▁▁▄▁▁▂▁▂▂▂▃█▄▁▁▁▁▂▁▂▁▁▁▁▁▁▂▆▃▁▁▁▁▁▁▁▁▂▃▂▃▃▃▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▁▂▄▃▄▆▅▁▁▁▁▁▁▂▂▁▆▂▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂
```

**Heap InUse** (current: 418.0MB | avg: 180.0MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,835 | 14,796 | +39 | 11,683 | 84,644 | decreasing (-5.54/hr) |
| Heap InUse | 418.0MB | 244.4MB | +173.6MB | 180.0MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 4533.2MB | 4532.7MB | +0.5MB | 2702.6MB | 6883.9MB | |
| Heap Objects | 1,868,614 | 1,420,046 | +448568 | 799,460 | 17,165,538 | |

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
| 2026-06-05 | 77 | 14,952 | 271.5MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 41.86MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 21.0MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 8.08MB |
| 6 | `bytes.growSlice` | 7.53MB |
| 7 | `runtime.mallocgc` | 7.51MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `bufio.NewReaderSize` | 5.03MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 46.77GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.64GB |
| 3 | `reflect.growslice` | 11.42GB |
| 4 | `jackskj/carta.getUniqueId` | 8.75GB |
| 5 | `reflect.unsafe_New` | 8.13GB |
| 6 | `fmt.(*buffer).writeString` | 7.96GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.5GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.17GB |
| 9 | `database/sql.convertAssignRows` | 5.79GB |
| 10 | `carta/value.NewCell` | 5.78GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 280.96MB | 271.33MB | 144.64MB | 0B |
| `evaluation.mergeMetadata` | 137.53MB | 133.53MB | 73.25MB | 0B |
| `local.(*Client).EvaluateV2` | 429.35MB | 414.93MB | 217.68MB | 0B |
| `local.topologicalSort` | 64.25MB | 63.24MB | 31.39MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 428.00MB | 417.64MB | 214.69MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 44.88MB | 40.30MB | 22.97MB | 0B |
| `localEvaluation.getMapOfValue` | 428.00MB | 417.64MB | 214.69MB | 0B |
| `utils.ParseFeatureFlag` | 429.00MB | 418.64MB | 215.41MB | 0B |

**Total FF alloc (current snapshot):** 2.19GB  |  **24h avg:** 1.11GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 97.44MB | 30/1319 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 77.54MB | 50/1319 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.56MB | 62/1319 | `██████░░░░░░░░░ 41%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 970/1319 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 18.3MB | 970/1319 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1319 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.43MB | 742/1319 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1319 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1319 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1319 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1319 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1319 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1319 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1319 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1319 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.23GB | 942/1319 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1319 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.66GB | 865/1319 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.77GB | 543/1319 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.66GB | 181/1319 | `█░░░░░░░░░░░░░░ 7%` |

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
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
