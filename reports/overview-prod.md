# Overview: prod
*Last updated: 2026-05-18 10:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T10:01 (128 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,569 | avg: 15,242 | max: 84,644 | trend: decreasing (-30.72/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄
```

**Heap InUse** (current: 373.5MB | avg: 207.5MB | max: 1896.6MB | trend: decreasing (-2.21MB/hr))
```
▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁▄▃▇
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 25%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,569 | 16,953 | +4616 | 15,242 | 84,644 | decreasing (-30.72/hr) |
| Heap InUse | 373.5MB | 223.1MB | +150.4MB | 207.5MB | 1896.6MB | decreasing (-2.21MB/hr) |
| Heap Sys | 4681.3MB | 4690.0MB | -8.7MB | 4198.8MB | 5842.7MB | |
| Heap Objects | 1,838,190 | 817,701 | +1020489 | 926,882 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 21 | 14,967 | 177.2MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 32.66MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 22.1MB |
| 4 | `bufio.NewReaderSize` | 16.06MB |
| 5 | `bufio.NewWriterSize` | 14.56MB |
| 6 | `runtime.mallocgc` | 12.1MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 10 | `net/http.(*Transport).dialConn` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 182.2GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 110.43GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 109.99GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 109.52GB |
| 5 | `experiment/local.topologicalSort` | 72.79GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 56.95GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 50.06GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 34.94GB |
| 9 | `segmentio/kafka-go.makePartitions` | 24.83GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 19.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/128 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 126/128 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 20.12MB | 126/128 | `████████░░░░░░░ 54%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/128 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/128 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/128 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/128 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.75MB | 60/128 | `█████░░░░░░░░░░ 34%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.44MB | 31/128 | `████░░░░░░░░░░░ 28%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 10.4MB | 9/128 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.81GB | 121/128 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 40.4GB | 117/128 | `██████████░░░░░ 72%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/128 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 24.01GB | 123/128 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 23.97GB | 123/128 | `██████░░░░░░░░░ 42%` |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 23.49GB | 119/128 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.growslice` | 20.37GB | 36/128 | `█████░░░░░░░░░░ 36%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/128 | `████░░░░░░░░░░░ 31%` |
| 9 | `experiment/local.topologicalSort` | 16.85GB | 105/128 | `████░░░░░░░░░░░ 30%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.8GB | 73/128 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
