# Overview: prod
*Last updated: 2026-05-25 14:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T14:30 (500 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,098 | avg: 15,602 | max: 84,644 | trend: decreasing (-1.01/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁▁▁▁▁▂▃▁▃
```

**Heap InUse** (current: 407.2MB | avg: 228.9MB | max: 1896.6MB | trend: stable (-0.12MB/hr))
```
▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▃▃▅▃▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,098 | 15,279 | +3819 | 15,602 | 84,644 | decreasing (-1.01/hr) |
| Heap InUse | 407.2MB | 321.5MB | +85.7MB | 228.9MB | 1896.6MB | stable (-0.12MB/hr) |
| Heap Sys | 4826.2MB | 4826.5MB | -0.3MB | 4157.9MB | 6883.9MB | |
| Heap Objects | 1,220,235 | 1,467,649 | -247414 | 985,603 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 30 | 15,496 | 225.8MB | 478.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 58.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 30.35MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.07MB |
| 5 | `bufio.NewWriterSize` | 11.54MB |
| 6 | `bufio.NewReaderSize` | 10.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 65.66GB |
| 2 | `reflect.growslice` | 28.51GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 25.01GB |
| 4 | `jackskj/carta.getUniqueId` | 24.92GB |
| 5 | `reflect.unsafe_New` | 22.26GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.29GB |
| 7 | `fmt.(*buffer).writeString` | 16.24GB |
| 8 | `carta/value.NewCell` | 16.21GB |
| 9 | `segmentio/kafka-go.makePartitions` | 13.56GB |
| 10 | `fmt.Sprintf` | 12.43GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 47.44MB | 20/500 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/500 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 498/500 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 29.69MB | 24/500 | `█████████░░░░░░ 62%` |
| 5 | `runtime.mallocgc` | 22.13MB | 498/500 | `██████░░░░░░░░░ 46%` |
| 6 | `bytes.growSlice` | 13.55MB | 327/500 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/500 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/500 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/500 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/500 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/500 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/500 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/500 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/500 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.08GB | 475/500 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/500 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/500 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.35GB | 432/500 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 18.11GB | 202/500 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.3GB | 300/500 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
