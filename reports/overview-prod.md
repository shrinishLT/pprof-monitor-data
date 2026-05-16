# Overview: prod
*Last updated: 2026-05-16 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T13:31 (39 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,389 | avg: 16,458 | max: 84,644 | trend: decreasing (-79.26/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 252.4MB | avg: 290.3MB | max: 1896.6MB | trend: stable (+0.20MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,389 | 14,208 | +181 | 16,458 | 84,644 | decreasing (-79.26/hr) |
| Heap InUse | 252.4MB | 206.0MB | +46.4MB | 290.3MB | 1896.6MB | stable (+0.20MB/hr) |
| Heap Sys | 5840.7MB | 5840.5MB | +0.2MB | 5207.9MB | 5842.7MB | |
| Heap Objects | 1,170,442 | 608,748 | +561694 | 1,138,355 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 29 | 17,198 | 307.8MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 39.06MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `database/sql.convertAssignRows` | 28.5MB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `bytes.growSlice` | 5.02MB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 4.5MB |
| 10 | `dotlapse-event-service/project.FilterProjectsByTags` | 2.54MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 80.46GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 79.07GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 48.92GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 48.68GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 35.94GB |
| 6 | `experiment/local.topologicalSort` | 32.12GB |
| 7 | `jackskj/carta.getUniqueId` | 27.86GB |
| 8 | `reflect.growslice` | 25.88GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.25GB |
| 10 | `fmt.(*buffer).writeString` | 21.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `runtime.mallocgc` | 39.25MB | 37/39 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 37/39 | `█████████████░░ 93%` |
| 3 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/39 | `███████████░░░░ 77%` |
| 4 | `net/http.(*Transport).dialConn` | 30.0MB | 1/39 | `███████████░░░░ 76%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 28.78MB | 7/39 | `██████████░░░░░ 73%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 27.04MB | 2/39 | `██████████░░░░░ 68%` |
| 7 | `bytes.growSlice` | 20.2MB | 22/39 | `███████░░░░░░░░ 51%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/39 | `██████░░░░░░░░░ 42%` |
| 9 | `crypto/tls.Client` | 16.51MB | 2/39 | `██████░░░░░░░░░ 42%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB | 1/39 | `██████░░░░░░░░░ 41%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 68.09GB | 34/39 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 50.83GB | 28/39 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 28.07GB | 34/39 | `██████░░░░░░░░░ 41%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.89GB | 34/39 | `██████░░░░░░░░░ 40%` |
| 5 | `reflect.growslice` | 25.43GB | 22/39 | `█████░░░░░░░░░░ 37%` |
| 6 | `fmt.(*buffer).writeString` | 24.82GB | 14/39 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 23.51GB | 33/39 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 20.31GB | 28/39 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 19.1GB | 16/39 | `████░░░░░░░░░░░ 28%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.55GB | 27/39 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.1x avg)
