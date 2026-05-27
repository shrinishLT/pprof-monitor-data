# Overview: prod
*Last updated: 2026-05-28 05:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T05:03 (622 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 0 | avg: 15,047 | max: 84,644 | trend: decreasing (-10.88/hr))
```
▃▃█▃▃▃▃▃▃▃▃▃▄▅▃▃▃▃▄▃▃▄▄▄▃▃▄▃▄▄▄▃▃▄▃▄▄▃▃▃▄▃▄▃▄▄▄▃▄▄▃▃▃▃▃▃▃▃▆▃▄▄▃▃▅▄▃▃▃▃▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 0.0MB | avg: 221.9MB | max: 1896.6MB | trend: stable (-0.20MB/hr))
```
▂▂█▂▄▂▂▂▂▂▂▂▄▆▄▂▂▂▃▂▂▅▃▃▂▂▅▂▃▃▃▂▂▃▂▃▄▂▂▃▃▃▄▃▂▄▃▂▃▂▇▅▂▂▂▂▃▃▅▄▅▃▂▂▅▃▃▃▄▂▃▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `░░░░░░░░░░░░░░░░░░░░ 0%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 0%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 0 | 0 | +0 | 15,047 | 84,644 | decreasing (-10.88/hr) |
| Heap InUse | 0.0MB | 0.0MB | +0.0MB | 221.9MB | 1896.6MB | stable (-0.20MB/hr) |
| Heap Sys | 0.0MB | 0.0MB | +0.0MB | 3923.2MB | 6883.9MB | |
| Heap Objects | 0 | 0 | +0 | 949,455 | 8,100,802 | |

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
| 2026-05-28 | 11 | 0 | 0.0MB | 0.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/622 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/622 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 597/622 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.36MB | 32/622 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.33MB | 597/622 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.26MB | 411/622 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/622 | `███░░░░░░░░░░░░ 25%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/622 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/622 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 590/622 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/622 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/622 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/622 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/622 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.3GB | 574/622 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/622 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/622 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.65GB | 527/622 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 16.69GB | 264/622 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.2GB | 380/622 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.2x avg)
