# Overview: prod
*Last updated: 2026-05-21 00:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T00:00 (257 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,154 | avg: 15,699 | max: 84,644 | trend: INCREASING (+11.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁
```

**Heap InUse** (current: 217.7MB | avg: 235.4MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▂▂▁▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,154 | 16,568 | -1414 | 15,699 | 84,644 | INCREASING (+11.46/hr) |
| Heap InUse | 217.7MB | 240.4MB | -22.7MB | 235.4MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4661.9MB | 4661.3MB | +0.6MB | 4306.2MB | 6579.6MB | |
| Heap Objects | 609,015 | 444,480 | +164535 | 993,305 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 1 | 15,154 | 217.7MB | 217.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 8.54MB |
| 6 | `bufio.NewReaderSize` | 5.55MB |
| 7 | `bufio.NewWriterSize` | 5.02MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 83.67GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 50.27GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 50.19GB |
| 4 | `experiment/local.topologicalSort` | 33.31GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.36GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 15.91GB |
| 7 | `reflect.growslice` | 8.43GB |
| 8 | `fmt.Sprintf` | 8.03GB |
| 9 | `jackskj/carta.getUniqueId` | 7.64GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.27GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/257 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/257 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 255/257 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/257 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.17MB | 255/257 | `█████░░░░░░░░░░ 38%` |
| 6 | `bytes.growSlice` | 13.99MB | 170/257 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/257 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/257 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/257 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.57MB | 34/257 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.77GB | 246/257 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.75GB | 252/257 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.7GB | 252/257 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.14GB | 238/257 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 48.9GB | 234/257 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.68GB | 202/257 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.78GB | 179/257 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/257 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/257 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.02GB | 102/257 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
