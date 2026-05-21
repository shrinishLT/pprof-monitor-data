# Overview: stage
*Last updated: 2026-05-21 12:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T12:02 (288 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,290 | max: 28,205 | trend: stable (+0.07/hr))
```
▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 140.1MB | avg: 167.5MB | max: 732.9MB | trend: stable (+0.30MB/hr))
```
▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,068 | -3 | 14,290 | 28,205 | stable (+0.07/hr) |
| Heap InUse | 140.1MB | 137.7MB | +2.4MB | 167.5MB | 732.9MB | stable (+0.30MB/hr) |
| Heap Sys | 1793.3MB | 1793.3MB | +0.0MB | 1325.0MB | 1793.5MB | |
| Heap Objects | 565,077 | 518,160 | +46917 | 864,362 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 32 | 14,118 | 171.0MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 235.59GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 137.66GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 136.96GB |
| 4 | `internal/evaluation.mergeMetadata` | 133.31GB |
| 5 | `reflect.unsafe_NewArray` | 101.68GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.15GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.4GB |
| 8 | `experiment/local.topologicalSort` | 68.1GB |
| 9 | `reflect.MakeSlice` | 56.75GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.73GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 286/288 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/288 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.7MB | 282/288 | `██████░░░░░░░░░ 40%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/288 | `████░░░░░░░░░░░ 30%` |
| 5 | `bytes.growSlice` | 10.81MB | 37/288 | `████░░░░░░░░░░░ 29%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/288 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 285/288 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 277/288 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/288 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/288 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 119.07GB | 279/288 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.57GB | 281/288 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.28GB | 280/288 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 69.67GB | 275/288 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 51.44GB | 279/288 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 49.59GB | 264/288 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.97GB | 277/288 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.5GB | 276/288 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 28.85GB | 277/288 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.59GB | 264/288 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
