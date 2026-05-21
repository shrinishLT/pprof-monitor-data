# Overview: stage
*Last updated: 2026-05-21 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T06:00 (269 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,392 | avg: 14,302 | max: 28,205 | trend: INCREASING (+0.67/hr))
```
▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▁▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▄▁▅
```

**Heap InUse** (current: 252.1MB | avg: 167.4MB | max: 732.9MB | trend: stable (+0.36MB/hr))
```
▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,392 | 14,067 | +325 | 14,302 | 28,205 | INCREASING (+0.67/hr) |
| Heap InUse | 252.1MB | 127.6MB | +124.5MB | 167.4MB | 732.9MB | stable (+0.36MB/hr) |
| Heap Sys | 1792.5MB | 1793.5MB | -1.0MB | 1291.9MB | 1793.5MB | |
| Heap Objects | 799,681 | 355,117 | +444564 | 863,769 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 13 | 14,119 | 173.8MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 28.6MB |
| 3 | `runtime.mallocgc` | 18.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `bytes.growSlice` | 5.53MB |
| 7 | `database/sql.convertAssignRows` | 4.5MB |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.55MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 224.76GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 134.16GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 133.41GB |
| 4 | `internal/evaluation.mergeMetadata` | 129.88GB |
| 5 | `reflect.unsafe_NewArray` | 97.01GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 80.55GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 67.79GB |
| 8 | `experiment/local.topologicalSort` | 66.41GB |
| 9 | `reflect.MakeSlice` | 54.13GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 35.11GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 267/269 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/269 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.46MB | 263/269 | `█████░░░░░░░░░░ 39%` |
| 4 | `bytes.growSlice` | 11.26MB | 35/269 | `████░░░░░░░░░░░ 30%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/269 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/269 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 266/269 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 258/269 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/269 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/269 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 110.95GB | 260/269 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.72GB | 262/269 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.44GB | 261/269 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 64.96GB | 256/269 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 47.94GB | 260/269 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.37GB | 245/269 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.52GB | 258/269 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 33.1GB | 257/269 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 26.89GB | 258/269 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.19GB | 245/269 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
