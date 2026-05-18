# Overview: stage
*Last updated: 2026-05-18 18:56 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:56 (149 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,087 | avg: 14,263 | max: 26,440 | trend: INCREASING (+9.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁█▁
```

**Heap InUse** (current: 141.2MB | avg: 154.5MB | max: 633.5MB | trend: INCREASING (+0.63MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▂▂▁▂▃▂▂▁▁█▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 53%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,087 | 26,440 | -12353 | 14,263 | 26,440 | INCREASING (+9.37/hr) |
| Heap InUse | 141.2MB | 633.5MB | -492.3MB | 154.5MB | 633.5MB | INCREASING (+0.63MB/hr) |
| Heap Sys | 1572.5MB | 1535.3MB | +37.2MB | 921.7MB | 1572.5MB | |
| Heap Objects | 466,632 | 1,851,798 | -1385166 | 831,621 | 1,851,798 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 42 | 14,586 | 174.1MB | 633.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 24.62MB |
| 3 | `runtime.mallocgc` | 17.01MB |
| 4 | `bufio.NewReaderSize` | 14.57MB |
| 5 | `bufio.NewWriterSize` | 12.59MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.06MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `compress/flate.NewWriter` | 4.41MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 118.78GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 82.9GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 82.07GB |
| 4 | `internal/evaluation.mergeMetadata` | 79.83GB |
| 5 | `reflect.unsafe_NewArray` | 51.42GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.85GB |
| 8 | `experiment/local.topologicalSort` | 40.91GB |
| 9 | `reflect.MakeSlice` | 28.49GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 147/149 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/149 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.48MB | 143/149 | `████░░░░░░░░░░░ 31%` |
| 4 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/149 | `████░░░░░░░░░░░ 29%` |
| 5 | `bytes.growSlice` | 9.42MB | 23/149 | `███░░░░░░░░░░░░ 25%` |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 146/149 | `███░░░░░░░░░░░░ 25%` |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 138/149 | `███░░░░░░░░░░░░ 24%` |
| 8 | `database/sql.convertAssignRows` | 8.5MB | 2/149 | `███░░░░░░░░░░░░ 23%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.2MB | 9/149 | `███░░░░░░░░░░░░ 22%` |
| 10 | `bufio.NewReaderSize` | 7.31MB | 13/149 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 59.29GB | 140/149 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.0GB | 125/149 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 25.63GB | 140/149 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 25.18GB | 136/149 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 25.1GB | 142/149 | `██████░░░░░░░░░ 42%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 24.95GB | 141/149 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.MakeSlice` | 14.46GB | 138/149 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 12.79GB | 137/149 | `███░░░░░░░░░░░░ 21%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.69GB | 138/149 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.19GB | 125/149 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (4.1x avg)
