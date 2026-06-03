# Overview: prod
*Last updated: 2026-06-04 04:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T04:30 (1009 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,765 | avg: 10,247 | max: 84,644 | trend: decreasing (-34.15/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅
```

**Heap InUse** (current: 662.1MB | avg: 153.3MB | max: 2823.8MB | trend: stable (-0.49MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,765 | 18,448 | -2683 | 10,247 | 84,644 | decreasing (-34.15/hr) |
| Heap InUse | 662.1MB | 319.6MB | +342.5MB | 153.3MB | 2823.8MB | stable (-0.49MB/hr) |
| Heap Sys | 726.7MB | 4528.4MB | -3801.7MB | 2577.9MB | 6883.9MB | |
| Heap Objects | 3,329,463 | 1,178,387 | +2151076 | 657,197 | 14,090,816 | |

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
| 2026-06-04 | 55 | 15,421 | 267.6MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 116.16MB |
| 2 | `database/sql.convertAssignRows` | 51.0MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bytes.growSlice` | 15.08MB |
| 5 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.16MB |
| 6 | `runtime.mallocgc` | 10.01MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 10 | `bufio.NewReaderSize` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 286.13MB |
| 2 | `fmt.Sprintf` | 250.41MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 243.95MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 225.44MB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 187.94MB |
| 6 | `jackskj/carta.getUniqueId` | 168.03MB |
| 7 | `reflect.growslice` | 143.23MB |
| 8 | `reflect.unsafe_New` | 135.06MB |
| 9 | `strconv.appendQuotedWith` | 131.74MB |
| 10 | `fmt.Sprint` | 114.63MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.12MB | 178.15MB | 90.03MB | 0B |
| `evaluation.mergeMetadata` | 2.00MB | 96.52MB | 46.94MB | 0B |
| `local.(*Client).EvaluateV2` | 5.66MB | 274.27MB | 139.08MB | 0B |
| `local.topologicalSort` | 0B | 40.55MB | 22.58MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.66MB | 267.26MB | 132.06MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 22.35MB | 15.61MB | 0B |
| `localEvaluation.getMapOfValue` | 5.66MB | 267.26MB | 132.06MB | 0B |
| `utils.ParseFeatureFlag` | 5.66MB | 267.26MB | 132.13MB | 0B |

**Total FF alloc (current snapshot):** 29.76MB  |  **24h avg:** 710.47MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 69.34MB | 28/1009 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1009 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 660/1009 | `███████░░░░░░░░ 52%` |
| 4 | `database/sql.convertAssignRows` | 34.25MB | 36/1009 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.43MB | 660/1009 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1009 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 13.17MB | 467/1009 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 18/1009 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1009 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1009 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1009 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1009 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1009 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1009 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 43.99GB | 637/1009 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1009 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1009 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.86GB | 580/1009 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.87GB | 327/1009 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1009 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.3x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
