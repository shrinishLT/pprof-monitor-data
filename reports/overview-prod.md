# Overview: prod
*Last updated: 2026-05-18 12:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T12:03 (132 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,377 | avg: 15,227 | max: 84,644 | trend: decreasing (-29.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁
```

**Heap InUse** (current: 283.7MB | avg: 210.2MB | max: 1896.6MB | trend: decreasing (-1.77MB/hr))
```
▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁▄▃▇▅▄▆▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,377 | 14,747 | +630 | 15,227 | 84,644 | decreasing (-29.32/hr) |
| Heap InUse | 283.7MB | 350.9MB | -67.2MB | 210.2MB | 1896.6MB | decreasing (-1.77MB/hr) |
| Heap Sys | 6168.0MB | 6167.3MB | +0.7MB | 4235.8MB | 6168.0MB | |
| Heap Objects | 1,063,668 | 1,680,914 | -617246 | 937,197 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 25 | 14,931 | 196.3MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.54MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bufio.NewWriterSize` | 4.52MB |
| 7 | `bufio.NewReaderSize` | 4.52MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 258.6GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 156.88GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 156.0GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 114.49GB |
| 5 | `experiment/local.topologicalSort` | 103.3GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 81.3GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 52.35GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 49.49GB |
| 9 | `reflect.growslice` | 30.13GB |
| 10 | `segmentio/kafka-go.makePartitions` | 27.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/132 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 130/132 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 21.2MB | 130/132 | `████████░░░░░░░ 57%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/132 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/132 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/132 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/132 | `█████░░░░░░░░░░ 35%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.67MB | 6/132 | `█████░░░░░░░░░░ 34%` |
| 9 | `bytes.growSlice` | 12.23MB | 64/132 | `████░░░░░░░░░░░ 33%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 10.4MB | 9/132 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.61GB | 125/132 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 46.92GB | 121/132 | `████████████░░░ 81%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 27.77GB | 127/132 | `███████░░░░░░░░ 48%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.75GB | 127/132 | `███████░░░░░░░░ 48%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 24.39GB | 123/132 | `██████░░░░░░░░░ 42%` |
| 6 | `fmt.(*buffer).writeString` | 24.13GB | 16/132 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.growslice` | 21.07GB | 40/132 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.8GB | 77/132 | `█████░░░░░░░░░░ 34%` |
| 9 | `experiment/local.topologicalSort` | 19.72GB | 109/132 | `█████░░░░░░░░░░ 34%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/132 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
