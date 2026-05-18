# Overview: stage
*Last updated: 2026-05-18 18:48 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:47 (146 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,097 | avg: 14,182 | max: 17,149 | trend: INCREASING (+3.17/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆▄▁
```

**Heap InUse** (current: 127.4MB | avg: 151.3MB | max: 290.3MB | trend: stable (+0.39MB/hr))
```
▂▃▃▂▁▁▂▂▂▁▁▁▃▃▂▃▃▃▃▃▃▅▃▄▁▃▃▂▄▃▂▁▂▂▃▂▃▃▁▃▂▂▃▂▂▃▂▁▁▁▃▁▁▁▁▃▄▁▂▄▂▁▁▃▃▁▃▃▂▇▄▂▂▁▁▃▂▁▁▂▃▃▄▁▂▄▂▁▃▄▃▄█▅▅▁
```

## Current Status

Goroutines: `████████████████░░░░ 82%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,097 | 15,507 | -1410 | 14,182 | 17,149 | INCREASING (+3.17/hr) |
| Heap InUse | 127.4MB | 231.4MB | -104.0MB | 151.3MB | 290.3MB | stable (+0.39MB/hr) |
| Heap Sys | 1334.5MB | 1330.7MB | +3.8MB | 910.2MB | 1334.5MB | |
| Heap Objects | 594,564 | 940,427 | -345863 | 826,279 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 39 | 14,308 | 163.4MB | 290.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 118.55GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.33GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.58GB |
| 4 | `internal/evaluation.mergeMetadata` | 69.63GB |
| 5 | `reflect.unsafe_NewArray` | 51.31GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.29GB |
| 8 | `experiment/local.topologicalSort` | 35.56GB |
| 9 | `reflect.MakeSlice` | 28.43GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 144/146 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/146 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.42MB | 141/146 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 144/146 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 136/146 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/146 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/146 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `bytes.growSlice` | 3.69MB | 21/146 | `█░░░░░░░░░░░░░░ 10%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.15MB | 124/146 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB | 7/146 | `█░░░░░░░░░░░░░░ 8%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 57.99GB | 137/146 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 27.54GB | 122/146 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 25.06GB | 137/146 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 24.03GB | 133/146 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 23.93GB | 139/146 | `██████░░░░░░░░░ 41%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 23.79GB | 138/146 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.MakeSlice` | 14.14GB | 135/146 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 12.2GB | 134/146 | `███░░░░░░░░░░░░ 21%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 12.09GB | 135/146 | `███░░░░░░░░░░░░ 20%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 11.99GB | 122/146 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
