# Overview: prod
*Last updated: 2026-05-18 16:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T16:02 (140 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,933 | avg: 15,282 | max: 84,644 | trend: decreasing (-20.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃
```

**Heap InUse** (current: 408.3MB | avg: 216.7MB | max: 1896.6MB | trend: decreasing (-0.96MB/hr))
```
▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,933 | 14,777 | +4156 | 15,282 | 84,644 | decreasing (-20.25/hr) |
| Heap InUse | 408.3MB | 327.7MB | +80.6MB | 216.7MB | 1896.6MB | decreasing (-0.96MB/hr) |
| Heap Sys | 6173.7MB | 6179.8MB | -6.1MB | 4346.5MB | 6179.8MB | |
| Heap Objects | 1,318,924 | 1,512,583 | -193659 | 951,631 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 33 | 15,233 | 227.4MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 33.67MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.07MB |
| 5 | `bufio.NewWriterSize` | 14.07MB |
| 6 | `bufio.NewReaderSize` | 12.06MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.01MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 353.75GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 214.3GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 213.53GB |
| 4 | `experiment/local.topologicalSort` | 141.38GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 128.38GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 111.07GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 67.68GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 58.74GB |
| 9 | `fmt.Sprintf` | 32.96GB |
| 10 | `segmentio/kafka-go.makePartitions` | 32.94GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/140 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 138/140 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 23.16MB | 138/140 | `█████████░░░░░░ 63%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/140 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/140 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/140 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/140 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.42MB | 72/140 | `█████░░░░░░░░░░ 33%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.72MB | 7/140 | `████░░░░░░░░░░░ 31%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.74MB | 38/140 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 63.8GB | 129/140 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 61.46GB | 133/140 | `██████████████░ 96%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 37.56GB | 135/140 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 37.54GB | 135/140 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 27.38GB | 85/140 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 27.09GB | 117/140 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.3GB | 131/140 | `██████░░░░░░░░░ 41%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/140 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.growslice` | 22.61GB | 47/140 | `█████░░░░░░░░░░ 35%` |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 18.83GB | 64/140 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
