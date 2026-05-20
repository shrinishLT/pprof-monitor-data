# Overview: prod
*Last updated: 2026-05-20 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T23:30 (256 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,568 | avg: 15,701 | max: 84,644 | trend: INCREASING (+11.69/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁
```

**Heap InUse** (current: 240.4MB | avg: 235.5MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▁▂▂▁▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,568 | 14,415 | +2153 | 15,701 | 84,644 | INCREASING (+11.69/hr) |
| Heap InUse | 240.4MB | 189.5MB | +50.9MB | 235.5MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4661.3MB | 4659.0MB | +2.3MB | 4304.8MB | 6579.6MB | |
| Heap Objects | 444,480 | 504,382 | -59902 | 994,806 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 16.08MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.03MB |
| 7 | `bufio.NewReaderSize` | 5.54MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.54MB |
| 10 | `reflect.unsafe_NewArray` | 2.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 80.95GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 48.61GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 48.52GB |
| 4 | `experiment/local.topologicalSort` | 32.22GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.49GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 15.38GB |
| 7 | `reflect.growslice` | 8.38GB |
| 8 | `fmt.Sprintf` | 7.71GB |
| 9 | `jackskj/carta.getUniqueId` | 7.6GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.23GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/256 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/256 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 254/256 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/256 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.12MB | 254/256 | `█████░░░░░░░░░░ 38%` |
| 6 | `bytes.growSlice` | 14.02MB | 169/256 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/256 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/256 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/256 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.57MB | 34/256 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.91GB | 245/256 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.83GB | 251/256 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.77GB | 251/256 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.14GB | 238/256 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 48.97GB | 233/256 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.76GB | 201/256 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.85GB | 178/256 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/256 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/256 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.13GB | 101/256 | `██░░░░░░░░░░░░░ 16%` |

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
