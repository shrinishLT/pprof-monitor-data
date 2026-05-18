# Overview: prod
*Last updated: 2026-05-18 15:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T15:33 (139 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,777 | avg: 15,255 | max: 84,644 | trend: decreasing (-22.98/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁
```

**Heap InUse** (current: 327.7MB | avg: 215.3MB | max: 1896.6MB | trend: decreasing (-1.10MB/hr))
```
▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,777 | 14,705 | +72 | 15,255 | 84,644 | decreasing (-22.98/hr) |
| Heap InUse | 327.7MB | 241.0MB | +86.7MB | 215.3MB | 1896.6MB | decreasing (-1.10MB/hr) |
| Heap Sys | 6179.8MB | 6176.5MB | +3.3MB | 4333.4MB | 6179.8MB | |
| Heap Objects | 1,512,583 | 629,031 | +883552 | 948,988 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 32 | 15,118 | 221.7MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bufio.NewWriterSize` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `bufio.NewReaderSize` | 1.52MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 339.86GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 205.94GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 205.13GB |
| 4 | `experiment/local.topologicalSort` | 135.85GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 128.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 106.69GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 65.11GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 58.73GB |
| 9 | `segmentio/kafka-go.makePartitions` | 32.27GB |
| 10 | `reflect.growslice` | 31.98GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/139 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 137/139 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 22.92MB | 137/139 | `█████████░░░░░░ 62%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/139 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/139 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/139 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/139 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.12MB | 71/139 | `████░░░░░░░░░░░ 32%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.72MB | 7/139 | `████░░░░░░░░░░░ 31%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.76MB | 10/139 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 61.53GB | 128/139 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 60.95GB | 132/139 | `██████████████░ 99%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 36.24GB | 134/139 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 36.23GB | 134/139 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.38GB | 84/139 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 26.1GB | 116/139 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.05GB | 130/139 | `██████░░░░░░░░░ 42%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/139 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.growslice` | 22.61GB | 47/139 | `█████░░░░░░░░░░ 36%` |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 18.05GB | 63/139 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
