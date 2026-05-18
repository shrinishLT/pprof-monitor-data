# Overview: prod
*Last updated: 2026-05-18 23:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T23:00 (159 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,904 | avg: 15,418 | max: 84,644 | trend: decreasing (-4.72/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁
```

**Heap InUse** (current: 287.2MB | avg: 230.0MB | max: 1896.6MB | trend: stable (+0.23MB/hr))
```
▁▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,904 | 15,525 | -621 | 15,418 | 84,644 | decreasing (-4.72/hr) |
| Heap InUse | 287.2MB | 291.6MB | -4.4MB | 230.0MB | 1896.6MB | stable (+0.23MB/hr) |
| Heap Sys | 6579.6MB | 6577.1MB | +2.5MB | 4584.7MB | 6579.6MB | |
| Heap Objects | 1,044,062 | 1,115,898 | -71836 | 986,854 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 52 | 15,668 | 264.1MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.unsafe_NewArray` | 4.01MB |
| 7 | `bytes.growSlice` | 3.52MB |
| 8 | `bufio.NewReaderSize` | 3.51MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 511.39GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 309.4GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 308.49GB |
| 4 | `experiment/local.topologicalSort` | 204.3GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 160.3GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 145.86GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 97.32GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 66.68GB |
| 9 | `fmt.Sprintf` | 51.0GB |
| 10 | `segmentio/kafka-go.makePartitions` | 42.23GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/159 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 157/159 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 27.01MB | 157/159 | `███████████░░░░ 73%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/159 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/159 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 13.17MB | 3/159 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 12.75MB | 90/159 | `█████░░░░░░░░░░ 34%` |
| 8 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/159 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/159 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.27MB | 54/159 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 111.95GB | 148/159 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 71.0GB | 152/159 | `█████████░░░░░░ 63%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 65.71GB | 154/159 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 65.59GB | 154/159 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 47.8GB | 136/159 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.51GB | 104/159 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.7GB | 83/159 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.95GB | 150/159 | `████░░░░░░░░░░░ 27%` |
| 9 | `fmt.Sprintf` | 27.69GB | 33/159 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/159 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
