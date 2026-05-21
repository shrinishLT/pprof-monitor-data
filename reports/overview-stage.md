# Overview: stage
*Last updated: 2026-05-21 09:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T09:30 (281 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,295 | max: 28,205 | trend: stable (+0.31/hr))
```
▃▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 141.6MB | avg: 167.8MB | max: 732.9MB | trend: stable (+0.34MB/hr))
```
▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,062 | +5 | 14,295 | 28,205 | stable (+0.31/hr) |
| Heap InUse | 141.6MB | 191.2MB | -49.6MB | 167.8MB | 732.9MB | stable (+0.34MB/hr) |
| Heap Sys | 1793.2MB | 1793.2MB | +0.0MB | 1313.3MB | 1793.5MB | |
| Heap Objects | 568,080 | 1,238,608 | -670528 | 866,114 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 25 | 14,132 | 175.6MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `segmentio/kafka-go.makeLayout` | 1.54MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 231.0GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 137.53GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 136.82GB |
| 4 | `internal/evaluation.mergeMetadata` | 133.16GB |
| 5 | `reflect.unsafe_NewArray` | 99.7GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.15GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.33GB |
| 8 | `experiment/local.topologicalSort` | 68.04GB |
| 9 | `reflect.MakeSlice` | 55.64GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.73GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 279/281 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/281 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.61MB | 275/281 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/281 | `████░░░░░░░░░░░ 30%` |
| 5 | `bytes.growSlice` | 10.81MB | 37/281 | `████░░░░░░░░░░░ 29%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/281 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 278/281 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 270/281 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/281 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/281 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 116.12GB | 272/281 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.86GB | 274/281 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.57GB | 273/281 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 68.0GB | 268/281 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 50.16GB | 272/281 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 48.46GB | 257/281 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.11GB | 270/281 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 34.65GB | 269/281 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 28.14GB | 270/281 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.1GB | 257/281 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
