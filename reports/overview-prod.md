# Overview: prod
*Last updated: 2026-05-21 21:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T21:30 (317 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,091 | avg: 15,769 | max: 84,644 | trend: INCREASING (+8.62/hr))
```
▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁
```

**Heap InUse** (current: 304.2MB | avg: 241.6MB | max: 1896.6MB | trend: stable (+0.37MB/hr))
```
▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,091 | 14,783 | +3308 | 15,769 | 84,644 | INCREASING (+8.62/hr) |
| Heap InUse | 304.2MB | 260.3MB | +43.9MB | 241.6MB | 1896.6MB | stable (+0.37MB/hr) |
| Heap Sys | 4879.5MB | 4879.2MB | +0.3MB | 4261.8MB | 6579.6MB | |
| Heap Objects | 997,247 | 1,329,793 | -332546 | 1,016,302 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 61 | 16,054 | 267.3MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 21.67MB |
| 4 | `bufio.NewWriterSize` | 13.05MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.06MB |
| 6 | `bufio.NewReaderSize` | 10.55MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 230.59GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 138.32GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 137.97GB |
| 4 | `experiment/local.topologicalSort` | 91.37GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 72.01GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 43.86GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 34.8GB |
| 8 | `fmt.Sprintf` | 24.05GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 16.0GB |
| 10 | `segmentio/kafka-go.makePartitions` | 15.21GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/317 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/317 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 315/317 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/317 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.88MB | 315/317 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.85MB | 226/317 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/317 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/317 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/317 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/317 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.38GB | 306/317 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.11GB | 312/317 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.09GB | 312/317 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.05GB | 293/317 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 47.92GB | 294/317 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.67GB | 262/317 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.97GB | 238/317 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.87GB | 257/317 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/317 | `███░░░░░░░░░░░░ 20%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.29GB | 160/317 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
