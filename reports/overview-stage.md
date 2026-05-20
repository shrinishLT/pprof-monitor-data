# Overview: stage
*Last updated: 2026-05-21 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T01:30 (260 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,308 | max: 28,205 | trend: INCREASING (+1.02/hr))
```
▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁▁▁▂▁
```

**Heap InUse** (current: 167.6MB | avg: 167.2MB | max: 732.9MB | trend: stable (+0.40MB/hr))
```
▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂▁▂▁▃▁▂▂▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,175 | -110 | 14,308 | 28,205 | INCREASING (+1.02/hr) |
| Heap InUse | 167.6MB | 165.7MB | +1.9MB | 167.2MB | 732.9MB | stable (+0.40MB/hr) |
| Heap Sys | 1790.9MB | 1790.9MB | +0.0MB | 1274.6MB | 1790.9MB | |
| Heap Objects | 927,419 | 851,424 | +75995 | 868,116 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 4 | 14,094 | 179.0MB | 203.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 216.53GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 130.23GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 129.48GB |
| 4 | `internal/evaluation.mergeMetadata` | 126.03GB |
| 5 | `reflect.unsafe_NewArray` | 93.44GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 65.71GB |
| 8 | `experiment/local.topologicalSort` | 64.45GB |
| 9 | `reflect.MakeSlice` | 52.18GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 258/260 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/260 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.33MB | 254/260 | `█████░░░░░░░░░░ 39%` |
| 4 | `bytes.growSlice` | 11.43MB | 34/260 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/260 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/260 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 257/260 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/260 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 249/260 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/260 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 107.0GB | 251/260 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.33GB | 253/260 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.05GB | 252/260 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.63GB | 247/260 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 46.23GB | 251/260 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.13GB | 236/260 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 32.3GB | 249/260 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 31.91GB | 248/260 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 25.94GB | 249/260 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.65GB | 236/260 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
