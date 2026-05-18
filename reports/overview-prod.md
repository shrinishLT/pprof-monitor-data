# Overview: prod
*Last updated: 2026-05-18 14:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T14:33 (137 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,442 | avg: 15,263 | max: 84,644 | trend: decreasing (-23.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁
```

**Heap InUse** (current: 268.7MB | avg: 214.3MB | max: 1896.6MB | trend: decreasing (-1.24MB/hr))
```
▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,442 | 14,533 | +909 | 15,263 | 84,644 | decreasing (-23.33/hr) |
| Heap InUse | 268.7MB | 310.8MB | -42.1MB | 214.3MB | 1896.6MB | decreasing (-1.24MB/hr) |
| Heap Sys | 6173.2MB | 6171.8MB | +1.4MB | 4306.4MB | 6173.2MB | |
| Heap Objects | 937,181 | 1,444,898 | -507717 | 947,210 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 30 | 15,143 | 217.6MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 11.06MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 7 | `bufio.NewWriterSize` | 4.52MB |
| 8 | `bufio.NewReaderSize` | 3.03MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 328.01GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 198.67GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 198.04GB |
| 4 | `experiment/local.topologicalSort` | 131.12GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 121.34GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 103.14GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 62.85GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 55.46GB |
| 9 | `reflect.growslice` | 31.79GB |
| 10 | `segmentio/kafka-go.makePartitions` | 30.95GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/137 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 135/137 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 22.45MB | 135/137 | `█████████░░░░░░ 61%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/137 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/137 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/137 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/137 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.35MB | 69/137 | `█████░░░░░░░░░░ 33%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.72MB | 7/137 | `████░░░░░░░░░░░ 31%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 36/137 | `████░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.96GB | 130/137 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 57.16GB | 126/137 | `██████████████░ 95%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 33.69GB | 132/137 | `████████░░░░░░░ 56%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.69GB | 132/137 | `████████░░░░░░░ 56%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.56GB | 128/137 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.44GB | 82/137 | `██████░░░░░░░░░ 40%` |
| 7 | `experiment/local.topologicalSort` | 24.19GB | 114/137 | `██████░░░░░░░░░ 40%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/137 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.growslice` | 22.19GB | 45/137 | `█████░░░░░░░░░░ 37%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/137 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
