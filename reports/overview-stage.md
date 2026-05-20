# Overview: stage
*Last updated: 2026-05-20 09:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T09:30 (228 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,077 | avg: 14,331 | max: 28,205 | trend: INCREASING (+2.92/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 182.7MB | avg: 166.1MB | max: 732.9MB | trend: INCREASING (+0.52MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▁▁▃▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,077 | 14,077 | +0 | 14,331 | 28,205 | INCREASING (+2.92/hr) |
| Heap InUse | 182.7MB | 149.9MB | +32.8MB | 166.1MB | 732.9MB | INCREASING (+0.52MB/hr) |
| Heap Sys | 1781.1MB | 1781.1MB | +0.0MB | 1202.8MB | 1781.1MB | |
| Heap Objects | 927,514 | 708,609 | +218905 | 860,763 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 20 | 14,122 | 184.0MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 187.7GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 119.66GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 118.98GB |
| 4 | `internal/evaluation.mergeMetadata` | 115.78GB |
| 5 | `reflect.unsafe_NewArray` | 81.05GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 76.12GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 60.3GB |
| 8 | `experiment/local.topologicalSort` | 59.26GB |
| 9 | `reflect.MakeSlice` | 45.25GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 226/228 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/228 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.8MB | 222/228 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/228 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/228 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/228 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 225/228 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/228 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 217/228 | `███░░░░░░░░░░░░ 24%` |
| 10 | `bufio.NewReaderSize` | 8.67MB | 20/228 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.04GB | 219/228 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 54.39GB | 221/228 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 54.14GB | 220/228 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 53.94GB | 215/228 | `████████░░░░░░░ 57%` |
| 5 | `reflect.unsafe_NewArray` | 40.22GB | 219/228 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.99GB | 204/228 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 27.76GB | 217/228 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 27.46GB | 216/228 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 22.57GB | 217/228 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.41GB | 204/228 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
