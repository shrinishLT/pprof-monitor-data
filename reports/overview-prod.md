# Overview: prod
*Last updated: 2026-05-20 13:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T13:02 (235 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,292 | avg: 15,505 | max: 84,644 | trend: INCREASING (+3.63/hr))
```
▂▁▁▁▁▂▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁
```

**Heap InUse** (current: 211.8MB | avg: 231.5MB | max: 1896.6MB | trend: stable (+0.15MB/hr))
```
▃▂▂▁▂▃▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,292 | 16,720 | -1428 | 15,505 | 84,644 | INCREASING (+3.63/hr) |
| Heap InUse | 211.8MB | 193.3MB | +18.5MB | 231.5MB | 1896.6MB | stable (+0.15MB/hr) |
| Heap Sys | 1016.3MB | 796.7MB | +219.6MB | 4415.2MB | 6579.6MB | |
| Heap Objects | 1,020,776 | 385,489 | +635287 | 982,106 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 27 | 16,369 | 239.0MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 9.05MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 6 | `bufio.NewReaderSize` | 4.02MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `bufio.NewWriterSize` | 2.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 53.25GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 32.01GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 31.88GB |
| 4 | `experiment/local.topologicalSort` | 21.26GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.63GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 10.07GB |
| 7 | `fmt.Sprintf` | 4.94GB |
| 8 | `reflect.growslice` | 3.92GB |
| 9 | `jackskj/carta.getUniqueId` | 3.62GB |
| 10 | `internal/evaluation.coerceString` | 3.42GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/235 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/235 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 233/235 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/235 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.64MB | 233/235 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/235 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.87MB | 148/235 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/235 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/235 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 229/235 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 123.1GB | 224/235 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.77GB | 230/235 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.7GB | 230/235 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 63.64GB | 222/235 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 51.35GB | 212/235 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.58GB | 180/235 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.12GB | 157/235 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.18GB | 210/235 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/235 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 22.0GB | 82/235 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
