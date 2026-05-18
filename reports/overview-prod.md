# Overview: prod
*Last updated: 2026-05-18 21:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T21:02 (155 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,823 | avg: 15,422 | max: 84,644 | trend: decreasing (-4.79/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁
```

**Heap InUse** (current: 339.4MB | avg: 229.0MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,823 | 14,850 | -27 | 15,422 | 84,644 | decreasing (-4.79/hr) |
| Heap InUse | 339.4MB | 256.5MB | +82.9MB | 229.0MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 6562.6MB | 6560.7MB | +1.9MB | 4533.2MB | 6573.6MB | |
| Heap Objects | 1,455,455 | 894,724 | +560731 | 988,928 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 48 | 15,701 | 263.7MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.04MB |
| 5 | `internal/evaluation.mergeMetadata` | 6.0MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `bufio.NewWriterSize` | 3.53MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `bufio.NewReaderSize` | 3.01MB |
| 10 | `experiment/local.(*Client).EvaluateV2` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 481.5GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 291.49GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 290.55GB |
| 4 | `experiment/local.topologicalSort` | 192.38GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 150.87GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 143.0GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 91.86GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 65.34GB |
| 9 | `fmt.Sprintf` | 47.72GB |
| 10 | `segmentio/kafka-go.makePartitions` | 39.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/155 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 153/155 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 26.28MB | 153/155 | `██████████░░░░░ 71%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/155 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/155 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 13.17MB | 3/155 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 12.92MB | 87/155 | `█████░░░░░░░░░░ 35%` |
| 8 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/155 | `████░░░░░░░░░░░ 31%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/155 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.7MB | 50/155 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 101.06GB | 144/155 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 69.03GB | 148/155 | `██████████░░░░░ 68%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 59.33GB | 150/155 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 59.23GB | 150/155 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 43.14GB | 132/155 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.09GB | 100/155 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.55GB | 79/155 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.0GB | 146/155 | `████░░░░░░░░░░░ 29%` |
| 9 | `fmt.Sprintf` | 24.58GB | 29/155 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/155 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
