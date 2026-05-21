# Overview: stage
*Last updated: 2026-05-21 08:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T08:00 (276 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,083 | avg: 14,299 | max: 28,205 | trend: INCREASING (+0.51/hr))
```
▁▁▁▁▁▂▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▁▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁
```

**Heap InUse** (current: 215.6MB | avg: 167.7MB | max: 732.9MB | trend: stable (+0.35MB/hr))
```
▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,083 | 14,067 | +16 | 14,299 | 28,205 | INCREASING (+0.51/hr) |
| Heap InUse | 215.6MB | 147.8MB | +67.8MB | 167.7MB | 732.9MB | stable (+0.35MB/hr) |
| Heap Sys | 1793.1MB | 1793.1MB | +0.0MB | 1304.6MB | 1793.5MB | |
| Heap Objects | 1,451,825 | 670,458 | +781367 | 864,642 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 20 | 14,148 | 176.6MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 228.31GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 137.43GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 136.72GB |
| 4 | `internal/evaluation.mergeMetadata` | 133.08GB |
| 5 | `reflect.unsafe_NewArray` | 98.55GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.15GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.29GB |
| 8 | `experiment/local.topologicalSort` | 67.99GB |
| 9 | `reflect.MakeSlice` | 54.99GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.73GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 274/276 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/276 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.55MB | 270/276 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/276 | `████░░░░░░░░░░░ 30%` |
| 5 | `bytes.growSlice` | 10.81MB | 37/276 | `████░░░░░░░░░░░ 29%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/276 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 273/276 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 265/276 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/276 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/276 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 113.99GB | 267/276 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.59GB | 269/276 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.3GB | 268/276 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 66.77GB | 263/276 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 49.25GB | 267/276 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.61GB | 252/276 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.46GB | 265/276 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 34.02GB | 264/276 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 27.62GB | 265/276 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.73GB | 252/276 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
