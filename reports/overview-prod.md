# Overview: prod
*Last updated: 2026-05-18 06:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T06:03 (120 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,692 | avg: 15,199 | max: 84,644 | trend: decreasing (-42.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 404.6MB | avg: 208.7MB | max: 1896.6MB | trend: decreasing (-2.57MB/hr))
```
█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂▁▁▁▁▁▄▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,692 | 15,683 | -991 | 15,199 | 84,644 | decreasing (-42.38/hr) |
| Heap InUse | 404.6MB | 303.1MB | +101.5MB | 208.7MB | 1896.6MB | decreasing (-2.57MB/hr) |
| Heap Sys | 4699.2MB | 4691.3MB | +7.9MB | 4165.7MB | 5842.7MB | |
| Heap Objects | 2,396,996 | 1,625,921 | +771075 | 934,940 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 13 | 14,395 | 169.4MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 40.53MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 31.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `runtime.mallocgc` | 8.58MB |
| 6 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 6.07MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `bytes.growSlice` | 4.53MB |
| 9 | `bufio.NewWriterSize` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 114.28GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 86.59GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 69.23GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 68.96GB |
| 5 | `experiment/local.topologicalSort` | 45.59GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 39.55GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.38GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 21.88GB |
| 9 | `segmentio/kafka-go.makePartitions` | 19.39GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 15.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/120 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 118/120 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/120 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.87MB | 118/120 | `████████░░░░░░░ 56%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/120 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/120 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/120 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.63MB | 54/120 | `█████░░░░░░░░░░ 34%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/120 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.37MB | 25/120 | `████░░░░░░░░░░░ 30%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.17GB | 113/120 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 33.53GB | 109/120 | `█████████░░░░░░ 64%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/120 | `██████░░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.66GB | 111/120 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/120 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 20.06GB | 115/120 | `█████░░░░░░░░░░ 38%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 19.98GB | 115/120 | `█████░░░░░░░░░░ 38%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/120 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/120 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 13.83GB | 97/120 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
