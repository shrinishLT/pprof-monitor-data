# Overview: stage
*Last updated: 2026-05-20 21:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T21:30 (252 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,219 | avg: 14,314 | max: 28,205 | trend: INCREASING (+1.45/hr))
```
▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁▃
```

**Heap InUse** (current: 162.0MB | avg: 167.1MB | max: 732.9MB | trend: stable (+0.43MB/hr))
```
▂▃▁▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,219 | 14,064 | +155 | 14,314 | 28,205 | INCREASING (+1.45/hr) |
| Heap InUse | 162.0MB | 140.5MB | +21.5MB | 167.1MB | 732.9MB | stable (+0.43MB/hr) |
| Heap Sys | 1789.5MB | 1788.7MB | +0.8MB | 1258.2MB | 1789.5MB | |
| Heap Objects | 719,990 | 564,606 | +155384 | 865,999 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 44 | 14,141 | 180.1MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bufio.NewWriterSize` | 2.54MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 209.39GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 129.31GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 128.54GB |
| 4 | `internal/evaluation.mergeMetadata` | 125.11GB |
| 5 | `reflect.unsafe_NewArray` | 90.28GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 65.24GB |
| 8 | `experiment/local.topologicalSort` | 64.0GB |
| 9 | `reflect.MakeSlice` | 50.4GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 250/252 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/252 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.21MB | 246/252 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 11.71MB | 33/252 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/252 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/252 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 249/252 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/252 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 241/252 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/252 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 103.5GB | 243/252 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 61.15GB | 245/252 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 60.88GB | 244/252 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 60.51GB | 239/252 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 44.73GB | 243/252 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.95GB | 228/252 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.19GB | 241/252 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 30.82GB | 240/252 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 25.09GB | 241/252 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.13GB | 228/252 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
