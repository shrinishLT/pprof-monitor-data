# Overview: prod
*Last updated: 2026-05-19 14:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T14:30 (190 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,070 | avg: 15,384 | max: 84,644 | trend: decreasing (-4.06/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁
```

**Heap InUse** (current: 251.1MB | avg: 229.3MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,070 | 14,781 | +289 | 15,384 | 84,644 | decreasing (-4.06/hr) |
| Heap InUse | 251.1MB | 246.3MB | +4.8MB | 229.3MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4944.6MB | 4945.0MB | -0.4MB | 4477.7MB | 6579.6MB | |
| Heap Objects | 1,221,137 | 1,164,925 | +56212 | 982,590 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 30 | 15,225 | 223.6MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `bytes.growSlice` | 9.57MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `bufio.NewReaderSize` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 89.53GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 53.6GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 53.58GB |
| 4 | `experiment/local.topologicalSort` | 35.63GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 28.2GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 17.0GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 14.63GB |
| 8 | `fmt.Sprintf` | 8.37GB |
| 9 | `jackskj/carta.getUniqueId` | 6.96GB |
| 10 | `reflect.growslice` | 6.95GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/190 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/190 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/190 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 188/190 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.13MB | 188/190 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/190 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/190 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.47MB | 17/190 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 12.09MB | 114/190 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/190 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.32GB | 179/190 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.73GB | 185/190 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.63GB | 185/190 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 67.98GB | 180/190 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 49.94GB | 167/190 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.32GB | 135/190 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.5GB | 113/190 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/190 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 25.62GB | 50/190 | `███░░░░░░░░░░░░ 21%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/190 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
