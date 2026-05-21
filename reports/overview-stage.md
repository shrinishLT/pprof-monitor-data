# Overview: stage
*Last updated: 2026-05-21 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T07:31 (275 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,300 | max: 28,205 | trend: INCREASING (+0.55/hr))
```
▁▁▁▁▁▁▂▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▁▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁
```

**Heap InUse** (current: 147.8MB | avg: 167.6MB | max: 732.9MB | trend: stable (+0.35MB/hr))
```
▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,300 | 28,205 | INCREASING (+0.55/hr) |
| Heap InUse | 147.8MB | 153.1MB | -5.3MB | 167.6MB | 732.9MB | stable (+0.35MB/hr) |
| Heap Sys | 1793.1MB | 1793.1MB | +0.0MB | 1302.8MB | 1793.5MB | |
| Heap Objects | 670,458 | 742,892 | -72434 | 862,507 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 19 | 14,151 | 174.5MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 227.42GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 137.39GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 136.67GB |
| 4 | `internal/evaluation.mergeMetadata` | 133.02GB |
| 5 | `reflect.unsafe_NewArray` | 98.17GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.15GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.25GB |
| 8 | `experiment/local.topologicalSort` | 67.96GB |
| 9 | `reflect.MakeSlice` | 54.76GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.73GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 273/275 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/275 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.54MB | 269/275 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/275 | `████░░░░░░░░░░░ 30%` |
| 5 | `bytes.growSlice` | 10.81MB | 37/275 | `████░░░░░░░░░░░ 29%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/275 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 272/275 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 264/275 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/275 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/275 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 113.56GB | 266/275 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.33GB | 268/275 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.04GB | 267/275 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 66.51GB | 262/275 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 49.06GB | 266/275 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.44GB | 251/275 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.33GB | 264/275 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 33.89GB | 263/275 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 27.52GB | 264/275 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.65GB | 251/275 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
