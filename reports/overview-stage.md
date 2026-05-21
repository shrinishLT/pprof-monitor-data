# Overview: stage
*Last updated: 2026-05-21 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T05:30 (268 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,301 | max: 28,205 | trend: INCREASING (+0.66/hr))
```
▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▁▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▄▁
```

**Heap InUse** (current: 127.6MB | avg: 167.0MB | max: 732.9MB | trend: stable (+0.35MB/hr))
```
▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,262 | -195 | 14,301 | 28,205 | INCREASING (+0.66/hr) |
| Heap InUse | 127.6MB | 190.4MB | -62.8MB | 167.0MB | 732.9MB | stable (+0.35MB/hr) |
| Heap Sys | 1793.5MB | 1792.1MB | +1.4MB | 1290.0MB | 1793.5MB | |
| Heap Objects | 355,117 | 788,071 | -432954 | 864,008 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 12 | 14,096 | 167.3MB | 203.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 223.78GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 133.99GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 133.24GB |
| 4 | `internal/evaluation.mergeMetadata` | 129.72GB |
| 5 | `reflect.unsafe_NewArray` | 96.55GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 67.71GB |
| 8 | `experiment/local.topologicalSort` | 66.33GB |
| 9 | `reflect.MakeSlice` | 53.92GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 266/268 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/268 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.44MB | 262/268 | `█████░░░░░░░░░░ 39%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/268 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/268 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/268 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 265/268 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/268 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 257/268 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/268 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 110.51GB | 259/268 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.46GB | 261/268 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.18GB | 260/268 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 64.7GB | 255/268 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 47.75GB | 259/268 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.23GB | 244/268 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.38GB | 257/268 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 32.97GB | 256/268 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 26.79GB | 257/268 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.12GB | 244/268 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
