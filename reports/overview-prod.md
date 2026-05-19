# Overview: prod
*Last updated: 2026-05-19 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T18:02 (197 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,122 | avg: 15,382 | max: 84,644 | trend: decreasing (-3.76/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 207.7MB | avg: 230.7MB | max: 1896.6MB | trend: stable (+0.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,122 | 17,248 | -2126 | 15,382 | 84,644 | decreasing (-3.76/hr) |
| Heap InUse | 207.7MB | 334.1MB | -126.4MB | 230.7MB | 1896.6MB | stable (+0.18MB/hr) |
| Heap Sys | 4938.2MB | 4949.7MB | -11.5MB | 4494.3MB | 6579.6MB | |
| Heap Objects | 706,496 | 1,576,498 | -870002 | 987,706 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 37 | 15,242 | 232.0MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 7.03MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 7 | `bufio.NewWriterSize` | 3.53MB |
| 8 | `bufio.NewReaderSize` | 2.51MB |
| 9 | `reflect.unsafe_NewArray` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 156.76GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 94.08GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 94.07GB |
| 4 | `experiment/local.topologicalSort` | 62.46GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.16GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.74GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.7GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.56GB |
| 9 | `fmt.Sprintf` | 15.46GB |
| 10 | `segmentio/kafka-go.makePartitions` | 10.38GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/197 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/197 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 195/197 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/197 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.92MB | 195/197 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/197 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/197 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.99MB | 120/197 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/197 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 193/197 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.51GB | 186/197 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.88GB | 192/197 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.78GB | 192/197 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.57GB | 187/197 | `████████░░░░░░░ 56%` |
| 5 | `experiment/local.topologicalSort` | 49.9GB | 174/197 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.89GB | 142/197 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.97GB | 120/197 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.16GB | 178/197 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/197 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 23.92GB | 57/197 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
