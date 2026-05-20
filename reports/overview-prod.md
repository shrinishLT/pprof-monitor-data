# Overview: prod
*Last updated: 2026-05-21 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T01:30 (260 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,187 | avg: 15,690 | max: 84,644 | trend: INCREASING (+10.66/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁
```

**Heap InUse** (current: 271.6MB | avg: 235.7MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,187 | 14,436 | +751 | 15,690 | 84,644 | INCREASING (+10.66/hr) |
| Heap InUse | 271.6MB | 297.3MB | -25.7MB | 235.7MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4852.3MB | 4837.7MB | +14.6MB | 4311.7MB | 6579.6MB | |
| Heap Objects | 1,089,954 | 1,425,587 | -335633 | 993,870 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 4 | 14,983 | 251.9MB | 297.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 8.04MB |
| 6 | `bufio.NewReaderSize` | 3.54MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 102.8GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 61.71GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 61.58GB |
| 4 | `experiment/local.topologicalSort` | 40.95GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 32.44GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 19.56GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 15.47GB |
| 8 | `fmt.Sprintf` | 9.97GB |
| 9 | `reflect.growslice` | 8.65GB |
| 10 | `jackskj/carta.getUniqueId` | 8.05GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/260 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/260 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 258/260 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/260 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.33MB | 258/260 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 13.85MB | 173/260 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/260 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/260 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/260 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.57MB | 35/260 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.49GB | 249/260 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.6GB | 255/260 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.54GB | 255/260 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 59.75GB | 240/260 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.76GB | 237/260 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.47GB | 205/260 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.6GB | 182/260 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/260 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/260 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.74GB | 105/260 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
