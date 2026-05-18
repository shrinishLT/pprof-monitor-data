# Overview: prod
*Last updated: 2026-05-18 22:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T22:30 (158 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,525 | avg: 15,421 | max: 84,644 | trend: decreasing (-4.56/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁
```

**Heap InUse** (current: 291.6MB | avg: 229.6MB | max: 1896.6MB | trend: stable (+0.21MB/hr))
```
▁▁▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,525 | 14,294 | +1231 | 15,421 | 84,644 | decreasing (-4.56/hr) |
| Heap InUse | 291.6MB | 210.7MB | +80.9MB | 229.6MB | 1896.6MB | stable (+0.21MB/hr) |
| Heap Sys | 6577.1MB | 6578.4MB | -1.3MB | 4572.0MB | 6578.4MB | |
| Heap Objects | 1,115,898 | 621,996 | +493902 | 986,492 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 51 | 15,683 | 263.7MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 5 | `bufio.NewReaderSize` | 5.52MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `bytes.growSlice` | 5.02MB |
| 8 | `reflect.mapassign_faststr0` | 4.0MB |
| 9 | `bufio.NewWriterSize` | 3.54MB |
| 10 | `crypto/tls.Client` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 504.98GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 305.51GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 304.68GB |
| 4 | `experiment/local.topologicalSort` | 201.73GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 158.25GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 143.0GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 96.13GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 65.34GB |
| 9 | `fmt.Sprintf` | 50.36GB |
| 10 | `segmentio/kafka-go.makePartitions` | 41.53GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/158 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 156/158 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 26.84MB | 156/158 | `██████████░░░░░ 73%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/158 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/158 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 13.17MB | 3/158 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 12.85MB | 89/158 | `█████░░░░░░░░░░ 34%` |
| 8 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/158 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/158 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.39MB | 53/158 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 109.23GB | 147/158 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 70.5GB | 151/158 | `█████████░░░░░░ 64%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 64.12GB | 153/158 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 64.01GB | 153/158 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 46.64GB | 135/158 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.41GB | 103/158 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.93GB | 82/158 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.71GB | 149/158 | `████░░░░░░░░░░░ 28%` |
| 9 | `fmt.Sprintf` | 26.96GB | 32/158 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/158 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
