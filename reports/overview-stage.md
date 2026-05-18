# Overview: stage
*Last updated: 2026-05-18 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:03 (144 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,503 | avg: 14,173 | max: 17,149 | trend: INCREASING (+2.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆
```

**Heap InUse** (current: 219.2MB | avg: 150.9MB | max: 290.3MB | trend: stable (+0.38MB/hr))
```
▂▃▂▃▃▂▁▁▂▂▂▁▁▁▃▃▂▃▃▃▃▃▃▅▃▄▁▃▃▂▄▃▂▁▂▂▃▂▃▃▁▃▂▂▃▂▂▃▂▁▁▁▃▁▁▁▁▃▄▁▂▄▂▁▁▃▃▁▃▃▂▇▄▂▂▁▁▃▂▁▁▂▃▃▄▁▂▄▂▁▃▄▃▄█▅
```

## Current Status

Goroutines: `███████████████████░ 96%`
Heap InUse: `████░░░░░░░░░░░░░░░░ 21%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,503 | 17,149 | -646 | 14,173 | 17,149 | INCREASING (+2.58/hr) |
| Heap InUse | 219.2MB | 290.3MB | -71.1MB | 150.9MB | 290.3MB | stable (+0.38MB/hr) |
| Heap Sys | 1007.8MB | 1002.8MB | +5.0MB | 904.3MB | 1016.6MB | |
| Heap Objects | 852,839 | 1,191,656 | -338817 | 827,096 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 37 | 14,282 | 162.6MB | 290.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 15.57MB |
| 3 | `runtime.mallocgc` | 12.1MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 9.04MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `bufio.NewWriterSize` | 7.04MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 117.22GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 59.15GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 58.46GB |
| 4 | `internal/evaluation.mergeMetadata` | 56.91GB |
| 5 | `reflect.unsafe_NewArray` | 50.75GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.49GB |
| 8 | `experiment/local.topologicalSort` | 29.03GB |
| 9 | `reflect.MakeSlice` | 28.12GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 142/144 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/144 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.38MB | 139/144 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 142/144 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 134/144 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/144 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/144 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `bytes.growSlice` | 3.59MB | 20/144 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.15MB | 122/144 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB | 6/144 | `█░░░░░░░░░░░░░░ 8%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 57.09GB | 135/144 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 27.21GB | 120/144 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 24.68GB | 135/144 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 23.33GB | 131/144 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 23.22GB | 137/144 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 23.09GB | 136/144 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 13.93GB | 133/144 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 11.85GB | 120/144 | `███░░░░░░░░░░░░ 20%` |
| 9 | `experiment/local.topologicalSort` | 11.84GB | 132/144 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.72GB | 133/144 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
