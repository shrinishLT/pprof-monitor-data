# Overview: prod
*Last updated: 2026-05-20 20:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T20:30 (250 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 26,148 | avg: 15,553 | max: 84,644 | trend: INCREASING (+5.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁▁▁▁▁▁▅
```

**Heap InUse** (current: 621.3MB | avg: 232.4MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂▁▁▂▁▂▅
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 30%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 26,148 | 15,792 | +10356 | 15,553 | 84,644 | INCREASING (+5.31/hr) |
| Heap InUse | 621.3MB | 252.1MB | +369.2MB | 232.4MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 4940.9MB | 4980.3MB | -39.4MB | 4342.0MB | 6579.6MB | |
| Heap Objects | 2,846,009 | 1,249,005 | +1597004 | 990,898 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 42 | 16,345 | 241.8MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 73.36MB |
| 2 | `bufio.NewWriterSize` | 38.69MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 34.66MB |
| 5 | `bufio.NewReaderSize` | 25.1MB |
| 6 | `runtime.mallocgc` | 19.13MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `internal/evaluation.mergeMetadata` | 8.5MB |
| 9 | `crypto/tls.Client` | 7.01MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 6.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 140.53GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 84.99GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 84.35GB |
| 4 | `experiment/local.topologicalSort` | 56.16GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.11GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 26.71GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 19.79GB |
| 8 | `fmt.Sprintf` | 15.59GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.54GB |
| 10 | `segmentio/kafka-go.makePartitions` | 10.03GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/250 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/250 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 248/250 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/250 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.01MB | 248/250 | `█████░░░░░░░░░░ 38%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/250 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 13.0MB | 163/250 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/250 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.95MB | 32/250 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/250 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.54GB | 239/250 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.76GB | 245/250 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.71GB | 245/250 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.39GB | 237/250 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.71GB | 227/250 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.6GB | 195/250 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.51GB | 172/250 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.98GB | 221/250 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/250 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.74GB | 97/250 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
