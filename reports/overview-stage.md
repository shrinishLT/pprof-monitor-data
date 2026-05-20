# Overview: stage
*Last updated: 2026-05-20 11:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T11:30 (232 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,327 | max: 28,205 | trend: INCREASING (+2.55/hr))
```
▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 133.0MB | avg: 165.7MB | max: 732.9MB | trend: stable (+0.48MB/hr))
```
▁▁▁▁▁▁▂▂▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,121 | -51 | 14,327 | 28,205 | INCREASING (+2.55/hr) |
| Heap InUse | 133.0MB | 160.4MB | -27.4MB | 165.7MB | 732.9MB | stable (+0.48MB/hr) |
| Heap Sys | 1781.2MB | 1781.2MB | +0.0MB | 1212.8MB | 1781.2MB | |
| Heap Objects | 447,891 | 732,075 | -284184 | 856,731 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 24 | 14,116 | 177.8MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 191.23GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 119.88GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 119.19GB |
| 4 | `internal/evaluation.mergeMetadata` | 115.99GB |
| 5 | `reflect.unsafe_NewArray` | 82.6GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 76.12GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 60.4GB |
| 8 | `experiment/local.topologicalSort` | 59.35GB |
| 9 | `reflect.MakeSlice` | 46.1GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 230/232 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/232 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.88MB | 226/232 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/232 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/232 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/232 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 229/232 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/232 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 221/232 | `███░░░░░░░░░░░░ 24%` |
| 10 | `bufio.NewReaderSize` | 8.67MB | 20/232 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.78GB | 223/232 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 55.55GB | 225/232 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 55.3GB | 224/232 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 55.07GB | 219/232 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 40.97GB | 223/232 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.68GB | 208/232 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 28.35GB | 221/232 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 28.04GB | 220/232 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 22.99GB | 221/232 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.71GB | 208/232 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
