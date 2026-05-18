# Overview: prod
*Last updated: 2026-05-18 19:04 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T19:04 (151 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,578 | avg: 15,359 | max: 84,644 | trend: decreasing (-10.27/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃
```

**Heap InUse** (current: 408.4MB | avg: 224.4MB | max: 1896.6MB | trend: stable (-0.19MB/hr))
```
▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▁▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆▄▄▃▅▅▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,578 | 18,920 | +658 | 15,359 | 84,644 | decreasing (-10.27/hr) |
| Heap InUse | 408.4MB | 378.3MB | +30.1MB | 224.4MB | 1896.6MB | stable (-0.19MB/hr) |
| Heap Sys | 6168.8MB | 6168.4MB | +0.4MB | 4479.5MB | 6179.8MB | |
| Heap Objects | 1,347,490 | 1,284,179 | +63311 | 973,103 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 44 | 15,510 | 250.9MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 25.13MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 20.6MB |
| 5 | `bufio.NewWriterSize` | 17.58MB |
| 6 | `bufio.NewReaderSize` | 14.56MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 5.01MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 423.81GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 256.67GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 255.93GB |
| 4 | `experiment/local.topologicalSort` | 169.29GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 132.92GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 81.04GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.91GB |
| 9 | `fmt.Sprintf` | 41.1GB |
| 10 | `segmentio/kafka-go.makePartitions` | 36.98GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/151 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 149/151 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 25.51MB | 149/151 | `██████████░░░░░ 69%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/151 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/151 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/151 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 12.44MB | 83/151 | `█████░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/151 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/151 | `████░░░░░░░░░░░ 28%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/151 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 90.69GB | 140/151 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 67.03GB | 144/151 | `███████████░░░░ 73%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 53.26GB | 146/151 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 53.18GB | 146/151 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 38.82GB | 96/151 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 38.7GB | 128/151 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 29.03GB | 142/151 | `████░░░░░░░░░░░ 32%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 27.45GB | 75/151 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/151 | `███░░░░░░░░░░░░ 26%` |
| 10 | `reflect.growslice` | 22.61GB | 47/151 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
