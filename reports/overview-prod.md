# Overview: prod
*Last updated: 2026-05-21 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T23:30 (323 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,734 | avg: 15,780 | max: 84,644 | trend: INCREASING (+8.52/hr))
```
▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 278.5MB | avg: 242.1MB | max: 1896.6MB | trend: stable (+0.36MB/hr))
```
▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,734 | 14,543 | +1191 | 15,780 | 84,644 | INCREASING (+8.52/hr) |
| Heap InUse | 278.5MB | 255.3MB | +23.2MB | 242.1MB | 1896.6MB | stable (+0.36MB/hr) |
| Heap Sys | 4885.8MB | 4885.7MB | +0.1MB | 4273.4MB | 6579.6MB | |
| Heap Objects | 1,070,042 | 1,216,261 | -146219 | 1,015,190 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 67 | 16,080 | 267.4MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 10.05MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 7.03MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 7 | `bufio.NewReaderSize` | 6.54MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 259.15GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 155.4GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 155.1GB |
| 4 | `experiment/local.topologicalSort` | 102.74GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 81.02GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 49.26GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 44.48GB |
| 8 | `fmt.Sprintf` | 27.3GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 20.56GB |
| 10 | `segmentio/kafka-go.makePartitions` | 17.87GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/323 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/323 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 321/323 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/323 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.08MB | 321/323 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.88MB | 232/323 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/323 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/323 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/323 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.53MB | 47/323 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.92GB | 312/323 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.61GB | 318/323 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.6GB | 318/323 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.75GB | 299/323 | `██████░░░░░░░░░ 44%` |
| 5 | `experiment/local.topologicalSort` | 48.93GB | 300/323 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.48GB | 268/323 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.47GB | 244/323 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.71GB | 262/323 | `███░░░░░░░░░░░░ 21%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/323 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.59GB | 147/323 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
