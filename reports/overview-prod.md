# Overview: prod
*Last updated: 2026-05-18 18:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:33 (145 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,829 | avg: 15,314 | max: 84,644 | trend: decreasing (-15.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃
```

**Heap InUse** (current: 424.1MB | avg: 219.9MB | max: 1896.6MB | trend: decreasing (-0.61MB/hr))
```
▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,829 | 15,828 | +3001 | 15,314 | 84,644 | decreasing (-15.61/hr) |
| Heap InUse | 424.1MB | 305.7MB | +118.4MB | 219.9MB | 1896.6MB | decreasing (-0.61MB/hr) |
| Heap Sys | 6169.0MB | 6177.7MB | -8.7MB | 4409.5MB | 6179.8MB | |
| Heap Objects | 1,716,711 | 1,219,155 | +497556 | 955,542 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 38 | 15,363 | 238.2MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 24.18MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.56MB |
| 5 | `bufio.NewWriterSize` | 11.56MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewReaderSize` | 7.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 3.5MB |
| 10 | `crypto/tls.Client` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 413.24GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 250.23GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 249.53GB |
| 4 | `experiment/local.topologicalSort` | 165.01GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 129.54GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 79.03GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.91GB |
| 9 | `fmt.Sprintf` | 39.87GB |
| 10 | `segmentio/kafka-go.makePartitions` | 36.27GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/145 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 143/145 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 24.27MB | 143/145 | `█████████░░░░░░ 66%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/145 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/145 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/145 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 12.47MB | 77/145 | `█████░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/145 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/145 | `████░░░░░░░░░░░ 28%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/145 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 75.9GB | 134/145 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 64.06GB | 138/145 | `████████████░░░ 84%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 44.62GB | 140/145 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 44.57GB | 140/145 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 32.61GB | 90/145 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 32.33GB | 122/145 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 27.58GB | 136/145 | `█████░░░░░░░░░░ 36%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/145 | `████░░░░░░░░░░░ 31%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 22.85GB | 69/145 | `████░░░░░░░░░░░ 30%` |
| 10 | `reflect.growslice` | 22.61GB | 47/145 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
