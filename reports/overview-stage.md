# Overview: stage
*Last updated: 2026-05-18 18:53 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:53 (148 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 26,440 | avg: 14,264 | max: 26,440 | trend: INCREASING (+9.65/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁█
```

**Heap InUse** (current: 633.5MB | avg: 154.6MB | max: 633.5MB | trend: INCREASING (+0.65MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▂▂▁▂▃▂▂▁▁█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `████████░░░░░░░░░░░░ 41%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 26,440 | 14,078 | +12362 | 14,264 | 26,440 | INCREASING (+9.65/hr) |
| Heap InUse | 633.5MB | 163.9MB | +469.6MB | 154.6MB | 633.5MB | INCREASING (+0.65MB/hr) |
| Heap Sys | 1535.3MB | 1334.6MB | +200.7MB | 917.3MB | 1535.3MB | |
| Heap Objects | 1,851,798 | 956,273 | +895525 | 834,087 | 1,851,798 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 41 | 14,599 | 174.9MB | 633.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 114.57MB |
| 2 | `bufio.NewReaderSize` | 49.2MB |
| 3 | `bufio.NewWriterSize` | 48.23MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 40.69MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 34.59MB |
| 7 | `internal/evaluation.mergeMetadata` | 34.01MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 30.9MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.13MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 17.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 118.7GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 82.82GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 82.0GB |
| 4 | `internal/evaluation.mergeMetadata` | 79.76GB |
| 5 | `reflect.unsafe_NewArray` | 51.37GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.82GB |
| 8 | `experiment/local.topologicalSort` | 40.87GB |
| 9 | `reflect.MakeSlice` | 28.47GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 146/148 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/148 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.44MB | 142/148 | `████░░░░░░░░░░░ 31%` |
| 4 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/148 | `████░░░░░░░░░░░ 29%` |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 145/148 | `███░░░░░░░░░░░░ 25%` |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 137/148 | `███░░░░░░░░░░░░ 24%` |
| 7 | `bytes.growSlice` | 8.73MB | 22/148 | `███░░░░░░░░░░░░ 23%` |
| 8 | `database/sql.convertAssignRows` | 8.5MB | 2/148 | `███░░░░░░░░░░░░ 23%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.72MB | 8/148 | `███░░░░░░░░░░░░ 21%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 7.67MB | 3/148 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 58.86GB | 139/148 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 27.85GB | 124/148 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 25.44GB | 139/148 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 24.78GB | 135/148 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 24.69GB | 141/148 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 24.55GB | 140/148 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 14.35GB | 137/148 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 12.58GB | 136/148 | `███░░░░░░░░░░░░ 21%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.48GB | 137/148 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.13GB | 124/148 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (4.1x avg)
