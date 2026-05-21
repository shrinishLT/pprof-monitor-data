# Overview: prod
*Last updated: 2026-05-22 01:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T01:02 (328 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,366 | avg: 15,786 | max: 84,644 | trend: INCREASING (+8.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 312.9MB | avg: 242.4MB | max: 1896.6MB | trend: stable (+0.36MB/hr))
```
▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,366 | 18,568 | -202 | 15,786 | 84,644 | INCREASING (+8.36/hr) |
| Heap InUse | 312.9MB | 312.7MB | +0.2MB | 242.4MB | 1896.6MB | stable (+0.36MB/hr) |
| Heap Sys | 4875.4MB | 4886.2MB | -10.8MB | 4282.7MB | 6579.6MB | |
| Heap Objects | 702,415 | 752,562 | -50147 | 1,012,287 | 8,100,802 | |

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
| 2026-05-22 | 4 | 16,301 | 262.0MB | 312.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 21.61MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.58MB |
| 5 | `bufio.NewWriterSize` | 10.54MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewReaderSize` | 8.55MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 5.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 5.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 276.61GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 165.75GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 165.43GB |
| 4 | `experiment/local.topologicalSort` | 109.65GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 86.42GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 52.56GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 47.93GB |
| 8 | `fmt.Sprintf` | 29.29GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 22.15GB |
| 10 | `segmentio/kafka-go.makePartitions` | 19.88GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/328 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/328 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 326/328 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/328 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.24MB | 326/328 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.93MB | 235/328 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/328 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/328 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/328 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.53MB | 47/328 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.22GB | 317/328 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.97GB | 323/328 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.96GB | 323/328 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.64GB | 304/328 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 49.85GB | 305/328 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.21GB | 273/328 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.93GB | 249/328 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.63GB | 267/328 | `███░░░░░░░░░░░░ 21%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/328 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 17.92GB | 152/328 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
