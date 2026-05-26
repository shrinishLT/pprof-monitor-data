# Overview: prod
*Last updated: 2026-05-26 19:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T19:32 (556 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,591 | avg: 15,618 | max: 84,644 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▁
```

**Heap InUse** (current: 218.6MB | avg: 230.1MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▄▄▅▃▄▃▂▅▃▂▄▃▃▅▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▃▁▁▄▁▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,591 | 15,445 | +146 | 15,618 | 84,644 | stable (-0.38/hr) |
| Heap InUse | 218.6MB | 267.1MB | -48.5MB | 230.1MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 4308.1MB | 4307.4MB | +0.7MB | 4157.7MB | 6883.9MB | |
| Heap Objects | 1,080,454 | 1,492,661 | -412207 | 985,415 | 8,100,802 | |

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
| 2026-05-26 | 38 | 15,953 | 219.6MB | 639.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 16.01MB |
| 3 | `bytes.growSlice` | 10.11MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 5.03MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `bufio.NewReaderSize` | 2.51MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 23.31GB |
| 2 | `fmt.Sprintf` | 12.32GB |
| 3 | `segmentio/kafka-go.makePartitions` | 11.23GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 8.97GB |
| 5 | `jackskj/carta.getUniqueId` | 8.68GB |
| 6 | `reflect.growslice` | 8.57GB |
| 7 | `reflect.unsafe_New` | 7.59GB |
| 8 | `strconv.appendQuotedWith` | 6.05GB |
| 9 | `fmt.Sprint` | 5.99GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 5.84GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 48.86MB | 21/556 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/556 | `██████████████░ 96%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 554/556 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.37MB | 27/556 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 22.86MB | 554/556 | `███████░░░░░░░░ 46%` |
| 6 | `bytes.growSlice` | 13.42MB | 373/556 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/556 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/556 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/556 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/556 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/556 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/556 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/556 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/556 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.16GB | 531/556 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/556 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/556 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.58GB | 487/556 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 17.47GB | 235/556 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.69GB | 348/556 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
