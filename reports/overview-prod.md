# Overview: prod
*Last updated: 2026-05-19 15:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T15:31 (192 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,879 | avg: 15,382 | max: 84,644 | trend: decreasing (-4.08/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁
```

**Heap InUse** (current: 182.8MB | avg: 228.9MB | max: 1896.6MB | trend: stable (+0.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,879 | 14,439 | +1440 | 15,382 | 84,644 | decreasing (-4.08/hr) |
| Heap InUse | 182.8MB | 200.5MB | -17.7MB | 228.9MB | 1896.6MB | stable (+0.08MB/hr) |
| Heap Sys | 4946.0MB | 4945.1MB | +0.9MB | 4482.6MB | 6579.6MB | |
| Heap Objects | 362,521 | 931,808 | -569287 | 979,096 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 32 | 15,221 | 221.6MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `bytes.growSlice` | 10.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 5.31MB |
| 7 | `bufio.NewWriterSize` | 4.53MB |
| 8 | `bufio.NewReaderSize` | 4.02MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `internal/evaluation.mergeMetadata` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 106.88GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 64.09GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 63.99GB |
| 4 | `experiment/local.topologicalSort` | 42.48GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.54GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 20.3GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 19.2GB |
| 8 | `fmt.Sprintf` | 10.12GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 8.81GB |
| 10 | `jackskj/carta.getUniqueId` | 7.47GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/192 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/192 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/192 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 190/192 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.07MB | 190/192 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/192 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/192 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.07MB | 115/192 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/192 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/192 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.13GB | 181/192 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.64GB | 187/192 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.53GB | 187/192 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 67.42GB | 182/192 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 49.83GB | 169/192 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.1GB | 137/192 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.27GB | 115/192 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.56GB | 173/192 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 25.01GB | 52/192 | `███░░░░░░░░░░░░ 21%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/192 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
