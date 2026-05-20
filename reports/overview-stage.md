# Overview: stage
*Last updated: 2026-05-20 21:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T21:02 (251 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,315 | max: 28,205 | trend: INCREASING (+1.49/hr))
```
▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄▄▁
```

**Heap InUse** (current: 140.5MB | avg: 167.1MB | max: 732.9MB | trend: stable (+0.43MB/hr))
```
▁▂▃▁▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,317 | -253 | 14,315 | 28,205 | INCREASING (+1.49/hr) |
| Heap InUse | 140.5MB | 180.5MB | -40.0MB | 167.1MB | 732.9MB | stable (+0.43MB/hr) |
| Heap Sys | 1788.7MB | 1788.0MB | +0.7MB | 1256.1MB | 1788.7MB | |
| Heap Objects | 564,606 | 759,383 | -194777 | 866,581 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 43 | 14,139 | 180.5MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 208.51GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 128.14GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 127.35GB |
| 4 | `internal/evaluation.mergeMetadata` | 123.96GB |
| 5 | `reflect.unsafe_NewArray` | 89.91GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 64.61GB |
| 8 | `experiment/local.topologicalSort` | 63.42GB |
| 9 | `reflect.MakeSlice` | 50.2GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 249/251 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/251 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.2MB | 245/251 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 11.71MB | 33/251 | `████░░░░░░░░░░░ 31%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/251 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/251 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 248/251 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/251 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 240/251 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/251 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 103.06GB | 242/251 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 60.87GB | 244/251 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 60.6GB | 243/251 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 60.24GB | 238/251 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 44.54GB | 242/251 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.8GB | 227/251 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.05GB | 240/251 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 30.69GB | 239/251 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.99GB | 240/251 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.07GB | 227/251 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
