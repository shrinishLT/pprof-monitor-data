# Overview: prod
*Last updated: 2026-05-19 10:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T10:02 (181 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 26,874 | avg: 15,388 | max: 84,644 | trend: decreasing (-4.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 661.0MB | avg: 229.3MB | max: 1896.6MB | trend: stable (+0.12MB/hr))
```
▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 31%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 26,874 | 15,508 | +11366 | 15,388 | 84,644 | decreasing (-4.42/hr) |
| Heap InUse | 661.0MB | 199.9MB | +461.1MB | 229.3MB | 1896.6MB | stable (+0.12MB/hr) |
| Heap Sys | 3120.7MB | 3151.6MB | -30.9MB | 4485.7MB | 6579.6MB | |
| Heap Objects | 3,436,931 | 775,090 | +2661841 | 981,895 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 21 | 15,193 | 221.2MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 75.88MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 35.16MB |
| 4 | `internal/evaluation.mergeMetadata` | 33.51MB |
| 5 | `bufio.NewWriterSize` | 26.1MB |
| 6 | `bufio.NewReaderSize` | 22.59MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 17.41MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.51MB |
| 9 | `experiment/local.topologicalSort` | 14.17MB |
| 10 | `runtime.mallocgc` | 13.63MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 140.64GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 84.92GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 84.46GB |
| 4 | `experiment/local.topologicalSort` | 55.96GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.62GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.49GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.61GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.65GB |
| 9 | `reflect.growslice` | 16.96GB |
| 10 | `jackskj/carta.getUniqueId` | 14.02GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/181 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/181 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/181 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 179/181 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.43MB | 179/181 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/181 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/181 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.77MB | 15/181 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `bytes.growSlice` | 12.24MB | 106/181 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/181 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.83GB | 170/181 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.71GB | 176/181 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.6GB | 176/181 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.01GB | 174/181 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 51.61GB | 158/181 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.53GB | 126/181 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 34.47GB | 104/181 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/181 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/181 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/181 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
