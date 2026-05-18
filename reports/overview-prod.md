# Overview: prod
*Last updated: 2026-05-18 12:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T12:33 (133 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,625 | avg: 15,268 | max: 84,644 | trend: decreasing (-25.03/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄
```

**Heap InUse** (current: 491.8MB | avg: 212.3MB | max: 1896.6MB | trend: decreasing (-1.54MB/hr))
```
▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,625 | 15,377 | +5248 | 15,268 | 84,644 | decreasing (-25.03/hr) |
| Heap InUse | 491.8MB | 283.7MB | +208.1MB | 212.3MB | 1896.6MB | decreasing (-1.54MB/hr) |
| Heap Sys | 6167.9MB | 6168.0MB | -0.1MB | 4250.3MB | 6168.0MB | |
| Heap Objects | 2,001,416 | 1,063,668 | +937748 | 945,199 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 26 | 15,150 | 207.7MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `bytes.growSlice` | 44.12MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewReaderSize` | 17.57MB |
| 5 | `bufio.NewWriterSize` | 15.06MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.57MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 4.0MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 269.17GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 163.15GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 162.45GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 114.49GB |
| 5 | `experiment/local.topologicalSort` | 107.45GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 84.6GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 52.35GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 51.5GB |
| 9 | `reflect.growslice` | 30.41GB |
| 10 | `segmentio/kafka-go.makePartitions` | 28.25GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/133 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 131/133 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 21.45MB | 131/133 | `████████░░░░░░░ 58%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/133 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/133 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/133 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/133 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.72MB | 65/133 | `█████░░░░░░░░░░ 34%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.67MB | 6/133 | `█████░░░░░░░░░░ 34%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.37MB | 33/133 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.06GB | 126/133 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 48.74GB | 122/133 | `████████████░░░ 83%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 28.82GB | 128/133 | `███████░░░░░░░░ 49%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 28.81GB | 128/133 | `███████░░░░░░░░ 49%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 24.62GB | 124/133 | `██████░░░░░░░░░ 42%` |
| 6 | `fmt.(*buffer).writeString` | 24.13GB | 16/133 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.growslice` | 21.29GB | 41/133 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.63GB | 78/133 | `█████░░░░░░░░░░ 35%` |
| 9 | `experiment/local.topologicalSort` | 20.51GB | 110/133 | `█████░░░░░░░░░░ 35%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/133 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
