# Overview: prod
*Last updated: 2026-05-18 05:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T05:01 (118 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,385 | avg: 15,199 | max: 84,644 | trend: decreasing (-44.55/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 142.4MB | avg: 206.2MB | max: 1896.6MB | trend: decreasing (-2.96MB/hr))
```
▄▅█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,385 | 14,069 | +316 | 15,199 | 84,644 | decreasing (-44.55/hr) |
| Heap InUse | 142.4MB | 114.4MB | +28.0MB | 206.2MB | 1896.6MB | decreasing (-2.96MB/hr) |
| Heap Sys | 4699.0MB | 4699.3MB | -0.3MB | 4156.7MB | 5842.7MB | |
| Heap Objects | 685,233 | 505,265 | +179968 | 916,694 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 11 | 14,251 | 135.8MB | 156.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `reflect.unsafe_New` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.03MB |
| 8 | `jackskj/carta.getUniqueId` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.52MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 70.87GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 69.49GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 42.81GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 42.72GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 31.75GB |
| 6 | `experiment/local.topologicalSort` | 28.33GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.63GB |
| 8 | `segmentio/kafka-go.makePartitions` | 18.17GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 13.54GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.25GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 116/118 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/118 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/118 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 21.08MB | 116/118 | `████████░░░░░░░ 57%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/118 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/118 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/118 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.78MB | 53/118 | `█████░░░░░░░░░░ 34%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/118 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.7MB | 24/118 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.67GB | 111/118 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 32.15GB | 107/118 | `█████████░░░░░░ 62%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/118 | `███████░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.38GB | 109/118 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/118 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.26GB | 113/118 | `█████░░░░░░░░░░ 37%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 19.18GB | 113/118 | `█████░░░░░░░░░░ 37%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/118 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/118 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 13.22GB | 95/118 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
