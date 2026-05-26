# Overview: prod
*Last updated: 2026-05-26 16:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T16:01 (549 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,500 | avg: 15,613 | max: 84,644 | trend: decreasing (-0.51/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 198.0MB | avg: 230.0MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▁▅▂▄▂▂▃▃▅▃▄▃▂▄▂▂▃▃▃▄▂▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁▇▁▃▁▁▁▁▁▁▁▄▅▃▁▁▁▂▁▁▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,500 | 20,241 | -4741 | 15,613 | 84,644 | decreasing (-0.51/hr) |
| Heap InUse | 198.0MB | 394.5MB | -196.5MB | 230.0MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 3454.0MB | 3450.2MB | +3.8MB | 4163.5MB | 6883.9MB | |
| Heap Objects | 639,440 | 1,530,684 | -891244 | 984,663 | 8,100,802 | |

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
| 2026-05-26 | 31 | 15,941 | 215.2MB | 639.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.51MB |
| 3 | `bytes.growSlice` | 9.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 8.07MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.54MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `aws/endpoints.init` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.9GB |
| 2 | `fmt.Sprintf` | 7.84GB |
| 3 | `reflect.growslice` | 7.6GB |
| 4 | `jackskj/carta.getUniqueId` | 7.56GB |
| 5 | `reflect.unsafe_New` | 6.51GB |
| 6 | `segmentio/kafka-go.makePartitions` | 6.47GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.11GB |
| 8 | `carta/value.NewCell` | 4.7GB |
| 9 | `fmt.(*buffer).writeString` | 4.51GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 3.87GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 48.86MB | 21/549 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/549 | `██████████████░ 96%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 547/549 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.37MB | 27/549 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 22.95MB | 547/549 | `███████░░░░░░░░ 46%` |
| 6 | `bytes.growSlice` | 13.39MB | 367/549 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/549 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/549 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/549 | `███░░░░░░░░░░░░ 21%` |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 10.5MB | 8/549 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/549 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/549 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/549 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/549 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.58GB | 524/549 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/549 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/549 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.8GB | 480/549 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 17.68GB | 228/549 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.8GB | 341/549 | `█░░░░░░░░░░░░░░ 11%` |

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
