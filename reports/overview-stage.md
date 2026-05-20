# Overview: stage
*Last updated: 2026-05-21 01:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T01:00 (259 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,175 | avg: 14,309 | max: 28,205 | trend: INCREASING (+1.08/hr))
```
▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁▁▁▂
```

**Heap InUse** (current: 165.7MB | avg: 167.2MB | max: 732.9MB | trend: stable (+0.40MB/hr))
```
▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂▁▂▁▃▁▂▂▃▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,175 | 14,071 | +104 | 14,309 | 28,205 | INCREASING (+1.08/hr) |
| Heap InUse | 165.7MB | 203.5MB | -37.8MB | 167.2MB | 732.9MB | stable (+0.40MB/hr) |
| Heap Sys | 1790.9MB | 1790.9MB | +0.0MB | 1272.6MB | 1790.9MB | |
| Heap Objects | 851,424 | 1,358,965 | -507541 | 867,887 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 3 | 14,104 | 182.8MB | 203.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 215.7GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 130.19GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 129.44GB |
| 4 | `internal/evaluation.mergeMetadata` | 125.99GB |
| 5 | `reflect.unsafe_NewArray` | 93.05GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 65.7GB |
| 8 | `experiment/local.topologicalSort` | 64.44GB |
| 9 | `reflect.MakeSlice` | 51.97GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 257/259 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/259 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.32MB | 253/259 | `█████░░░░░░░░░░ 39%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/259 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/259 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/259 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 256/259 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/259 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 248/259 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/259 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 106.57GB | 250/259 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.06GB | 252/259 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 62.79GB | 251/259 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.37GB | 246/259 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 46.05GB | 250/259 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.99GB | 235/259 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 32.16GB | 248/259 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 31.77GB | 247/259 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 25.83GB | 248/259 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.58GB | 235/259 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
