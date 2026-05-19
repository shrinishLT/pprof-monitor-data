# Overview: prod
*Last updated: 2026-05-19 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T20:02 (201 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,406 | avg: 15,401 | max: 84,644 | trend: decreasing (-2.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃
```

**Heap InUse** (current: 305.8MB | avg: 231.0MB | max: 1896.6MB | trend: stable (+0.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,406 | 15,383 | +4023 | 15,401 | 84,644 | decreasing (-2.37/hr) |
| Heap InUse | 305.8MB | 254.7MB | +51.1MB | 231.0MB | 1896.6MB | stable (+0.18MB/hr) |
| Heap Sys | 4942.4MB | 4942.2MB | +0.2MB | 4503.2MB | 6579.6MB | |
| Heap Objects | 953,648 | 1,205,076 | -251428 | 986,323 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 41 | 15,353 | 233.3MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.69MB |
| 3 | `runtime.mallocgc` | 20.22MB |
| 4 | `bufio.NewReaderSize` | 16.58MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.06MB |
| 6 | `bufio.NewWriterSize` | 10.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 189.47GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 113.87GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 113.78GB |
| 4 | `experiment/local.topologicalSort` | 75.53GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.94GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 58.3GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 35.94GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.77GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 20.39GB |
| 10 | `fmt.Sprintf` | 19.16GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/201 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/201 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 199/201 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/201 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.8MB | 199/201 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/201 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/201 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 12.08MB | 124/201 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/201 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 197/201 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.72GB | 190/201 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.62GB | 196/201 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.52GB | 196/201 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.33GB | 191/201 | `████████░░░░░░░ 55%` |
| 5 | `experiment/local.topologicalSort` | 50.36GB | 178/201 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.11GB | 146/201 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.02GB | 124/201 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.06GB | 182/201 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/201 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 23.51GB | 61/201 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
