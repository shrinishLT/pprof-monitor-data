# Overview: prod
*Last updated: 2026-05-18 02:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T02:02 (112 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,118 | avg: 15,253 | max: 84,644 | trend: decreasing (-46.05/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 149.1MB | avg: 210.0MB | max: 1896.6MB | trend: decreasing (-3.03MB/hr))
```
█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,118 | 14,067 | +1051 | 15,253 | 84,644 | decreasing (-46.05/hr) |
| Heap InUse | 149.1MB | 137.4MB | +11.7MB | 210.0MB | 1896.6MB | decreasing (-3.03MB/hr) |
| Heap Sys | 4163.1MB | 4165.8MB | -2.7MB | 4127.6MB | 5842.7MB | |
| Heap Objects | 293,307 | 841,638 | -548331 | 930,740 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 5 | 14,314 | 135.5MB | 149.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 9.5MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `runtime.mallocgc` | 8.58MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.78MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 4.75MB |
| 9 | `bufio.NewWriterSize` | 4.52MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 57.39GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 55.34GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 34.52GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 34.48GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.28GB |
| 6 | `experiment/local.topologicalSort` | 22.92GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.32GB |
| 8 | `segmentio/kafka-go.makePartitions` | 14.62GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 10.91GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.91GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 110/112 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/112 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/112 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.76MB | 110/112 | `████████░░░░░░░ 59%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/112 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/112 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/112 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 13.0MB | 52/112 | `█████░░░░░░░░░░ 35%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/112 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.7MB | 24/112 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.92GB | 105/112 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.15GB | 101/112 | `████████░░░░░░░ 59%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/112 | `███████░░░░░░░░ 47%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 20.9GB | 103/112 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/112 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.12GB | 107/112 | `█████░░░░░░░░░░ 35%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.04GB | 107/112 | `█████░░░░░░░░░░ 35%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/112 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/112 | `████░░░░░░░░░░░ 31%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.42GB | 57/112 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
