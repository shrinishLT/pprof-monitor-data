# Overview: prod
*Last updated: 2026-06-04 14:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:35 (1130 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,112 | avg: 11,032 | max: 84,644 | trend: decreasing (-16.78/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 641.7MB | avg: 167.1MB | max: 2823.8MB | trend: stable (-0.21MB/hr))
```
▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,112 | 15,225 | +887 | 11,032 | 84,644 | decreasing (-16.78/hr) |
| Heap InUse | 641.7MB | 255.5MB | +386.2MB | 167.1MB | 2823.8MB | stable (-0.21MB/hr) |
| Heap Sys | 3419.8MB | 3419.6MB | +0.2MB | 2628.7MB | 6883.9MB | |
| Heap Objects | 4,045,436 | 1,434,606 | +2610830 | 720,251 | 14,090,816 | |

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
| 2026-06-04 | 176 | 16,907 | 277.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 80.81MB |
| 2 | `database/sql.convertAssignRows` | 52.0MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 45.82MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `runtime.mallocgc` | 11.01MB |
| 6 | `bytes.growSlice` | 10.05MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.61MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 10 | `bufio.NewWriterSize` | 5.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.84GB |
| 2 | `fmt.Sprintf` | 5.96GB |
| 3 | `reflect.growslice` | 5.71GB |
| 4 | `jackskj/carta.getUniqueId` | 5.33GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 5.21GB |
| 6 | `reflect.unsafe_New` | 4.62GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.29GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.22GB |
| 9 | `fmt.(*buffer).writeString` | 3.33GB |
| 10 | `carta/value.NewCell` | 3.3GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 375.91MB | 361.17MB | 225.46MB | 0B |
| `evaluation.mergeMetadata` | 193.55MB | 187.05MB | 119.50MB | 0B |
| `local.(*Client).EvaluateV2` | 573.98MB | 554.65MB | 341.45MB | 0B |
| `local.topologicalSort` | 80.48MB | 78.45MB | 47.41MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 543.35MB | 522.51MB | 327.67MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 87.45MB | 86.43MB | 45.22MB | 0B |
| `localEvaluation.getMapOfValue` | 543.35MB | 522.51MB | 327.67MB | 0B |
| `utils.ParseFeatureFlag` | 543.35MB | 522.51MB | 327.83MB | 0B |

**Total FF alloc (current snapshot):** 2.87GB  |  **24h avg:** 1.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1130 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1130 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 781/1130 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1130 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.28MB | 781/1130 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1130 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.31MB | 568/1130 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1130 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1130 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.44MB | 25/1130 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1130 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1130 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1130 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1130 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1130 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.15GB | 754/1130 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1130 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.71GB | 678/1130 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.62GB | 373/1130 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.27GB | 515/1130 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
