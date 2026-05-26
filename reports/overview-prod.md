# Overview: prod
*Last updated: 2026-05-27 00:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T00:33 (566 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,256 | avg: 15,612 | max: 84,644 | trend: stable (-0.50/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 222.4MB | avg: 229.6MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▄▄▅▃▄▃▂▅▃▂▄▃▃▅▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▃▁▁▄▁▃▂▂▁▁▂▁▂▃▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,256 | 14,724 | +532 | 15,612 | 84,644 | stable (-0.50/hr) |
| Heap InUse | 222.4MB | 167.1MB | +55.3MB | 229.6MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 4467.8MB | 4464.0MB | +3.8MB | 4162.6MB | 6883.9MB | |
| Heap Objects | 1,188,164 | 662,786 | +525378 | 981,579 | 8,100,802 | |

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
| 2026-05-27 | 2 | 14,990 | 194.8MB | 222.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 16.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 8.49MB |
| 5 | `bytes.growSlice` | 8.04MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `database/sql.convertAssignRows` | 3.5MB |
| 10 | `bufio.NewWriterSize` | 3.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 35.33GB |
| 2 | `fmt.Sprintf` | 18.1GB |
| 3 | `segmentio/kafka-go.makePartitions` | 18.02GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 13.6GB |
| 5 | `jackskj/carta.getUniqueId` | 11.5GB |
| 6 | `reflect.growslice` | 11.01GB |
| 7 | `reflect.unsafe_New` | 9.93GB |
| 8 | `reflect.unsafe_NewArray` | 9.33GB |
| 9 | `strconv.appendQuotedWith` | 8.88GB |
| 10 | `fmt.Sprint` | 8.82GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/566 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.02MB | 22/566 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 564/566 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 26.52MB | 28/566 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 22.73MB | 564/566 | `███████░░░░░░░░ 48%` |
| 6 | `bytes.growSlice` | 13.3MB | 381/566 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/566 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/566 | `███░░░░░░░░░░░░ 22%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/566 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/566 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/566 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/566 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/566 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/566 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.81GB | 541/566 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/566 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/566 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.36GB | 497/566 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.4GB | 245/566 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.69GB | 358/566 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
