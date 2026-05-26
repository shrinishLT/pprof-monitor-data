# Overview: prod
*Last updated: 2026-05-26 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T22:31 (562 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,859 | avg: 15,613 | max: 84,644 | trend: stable (-0.47/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 230.5MB | avg: 229.8MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▄▄▅▃▄▃▂▅▃▂▄▃▃▅▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▃▁▁▄▁▃▂▂▁▁▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,859 | 14,784 | +1075 | 15,613 | 84,644 | stable (-0.47/hr) |
| Heap InUse | 230.5MB | 163.6MB | +66.9MB | 229.8MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 4465.3MB | 4466.8MB | -1.5MB | 4160.4MB | 6883.9MB | |
| Heap Objects | 1,077,492 | 456,001 | +621491 | 982,508 | 8,100,802 | |

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
| 2026-05-26 | 44 | 15,847 | 216.3MB | 639.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 16.01MB |
| 3 | `bytes.growSlice` | 10.34MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 4.03MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `bufio.NewReaderSize` | 2.51MB |
| 10 | `aws/endpoints.init` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 30.53GB |
| 2 | `fmt.Sprintf` | 16.09GB |
| 3 | `segmentio/kafka-go.makePartitions` | 15.33GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 11.76GB |
| 5 | `jackskj/carta.getUniqueId` | 10.9GB |
| 6 | `reflect.growslice` | 10.56GB |
| 7 | `reflect.unsafe_New` | 9.45GB |
| 8 | `strconv.appendQuotedWith` | 7.87GB |
| 9 | `reflect.unsafe_NewArray` | 7.86GB |
| 10 | `fmt.Sprint` | 7.81GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 48.86MB | 21/562 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/562 | `██████████████░ 96%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 560/562 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.37MB | 27/562 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 22.78MB | 560/562 | `██████░░░░░░░░░ 46%` |
| 6 | `bytes.growSlice` | 13.34MB | 378/562 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/562 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/562 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/562 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/562 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/562 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/562 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/562 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/562 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.92GB | 537/562 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/562 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/562 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.43GB | 493/562 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.4GB | 241/562 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.67GB | 354/562 | `█░░░░░░░░░░░░░░ 11%` |

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
