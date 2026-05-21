# Overview: stage
*Last updated: 2026-05-21 06:35 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T06:35 (271 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,545 | avg: 14,303 | max: 28,205 | trend: INCREASING (+0.72/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▁▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█
```

**Heap InUse** (current: 193.0MB | avg: 167.6MB | max: 732.9MB | trend: stable (+0.37MB/hr))
```
▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,545 | 14,435 | +110 | 14,303 | 28,205 | INCREASING (+0.72/hr) |
| Heap InUse | 193.0MB | 211.3MB | -18.3MB | 167.6MB | 732.9MB | stable (+0.37MB/hr) |
| Heap Sys | 1793.0MB | 1792.6MB | +0.4MB | 1295.6MB | 1793.5MB | |
| Heap Objects | 764,746 | 756,361 | +8385 | 863,007 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 15 | 14,168 | 177.6MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `bytes.growSlice` | 4.02MB |
| 7 | `reflect.mapassign_faststr0` | 3.5MB |
| 8 | `bufio.NewWriterSize` | 3.04MB |
| 9 | `bufio.NewReaderSize` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 225.8GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 137.27GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 136.56GB |
| 4 | `internal/evaluation.mergeMetadata` | 132.92GB |
| 5 | `reflect.unsafe_NewArray` | 97.47GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.07GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.2GB |
| 8 | `experiment/local.topologicalSort` | 67.91GB |
| 9 | `reflect.MakeSlice` | 54.38GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 269/271 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/271 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.49MB | 265/271 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/271 | `████░░░░░░░░░░░ 30%` |
| 5 | `bytes.growSlice` | 10.81MB | 37/271 | `████░░░░░░░░░░░ 29%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/271 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 268/271 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 260/271 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/271 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/271 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 111.83GB | 262/271 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 66.26GB | 264/271 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.98GB | 263/271 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 65.48GB | 258/271 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 48.31GB | 262/271 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.73GB | 247/271 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.79GB | 260/271 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 33.36GB | 259/271 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 27.1GB | 260/271 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.34GB | 247/271 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
