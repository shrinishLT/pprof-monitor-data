# Overview: stage
*Last updated: 2026-05-18 18:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:33 (145 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,507 | avg: 14,183 | max: 17,149 | trend: INCREASING (+3.28/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▆▄
```

**Heap InUse** (current: 231.4MB | avg: 151.4MB | max: 290.3MB | trend: stable (+0.42MB/hr))
```
▃▂▃▃▂▁▁▂▂▂▁▁▁▃▃▂▃▃▃▃▃▃▅▃▄▁▃▃▂▄▃▂▁▂▂▃▂▃▃▁▃▂▂▃▂▂▃▂▁▁▁▃▁▁▁▁▃▄▁▂▄▂▁▁▃▃▁▃▃▂▇▄▂▂▁▁▃▂▁▁▂▃▃▄▁▂▄▂▁▃▄▃▄█▅▅
```

## Current Status

Goroutines: `██████████████████░░ 90%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,507 | 16,503 | -996 | 14,183 | 17,149 | INCREASING (+3.28/hr) |
| Heap InUse | 231.4MB | 219.2MB | +12.2MB | 151.4MB | 290.3MB | stable (+0.42MB/hr) |
| Heap Sys | 1330.7MB | 1007.8MB | +322.9MB | 907.2MB | 1330.7MB | |
| Heap Objects | 940,427 | 852,839 | +87588 | 827,878 | 1,405,098 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 38 | 14,314 | 164.4MB | 290.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `bufio.NewReaderSize` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 3.02MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 118.15GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.13GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.38GB |
| 4 | `internal/evaluation.mergeMetadata` | 69.42GB |
| 5 | `reflect.unsafe_NewArray` | 51.14GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.99GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.2GB |
| 8 | `experiment/local.topologicalSort` | 35.46GB |
| 9 | `reflect.MakeSlice` | 28.34GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 143/145 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/145 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 11.4MB | 140/145 | `████░░░░░░░░░░░ 31%` |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 143/145 | `███░░░░░░░░░░░░ 25%` |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 135/145 | `███░░░░░░░░░░░░ 24%` |
| 6 | `database/sql.convertAssignRows` | 8.5MB | 2/145 | `███░░░░░░░░░░░░ 23%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.43MB | 1/145 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `bytes.growSlice` | 3.69MB | 21/145 | `█░░░░░░░░░░░░░░ 10%` |
| 9 | `segmentio/kafka-go.makePartitions` | 3.15MB | 123/145 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB | 7/145 | `█░░░░░░░░░░░░░░ 8%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 57.54GB | 136/145 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 27.38GB | 121/145 | `███████░░░░░░░░ 47%` |
| 3 | `reflect.unsafe_NewArray` | 24.87GB | 136/145 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.mergeMetadata` | 23.68GB | 132/145 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 23.58GB | 138/145 | `██████░░░░░░░░░ 40%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 23.44GB | 137/145 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.MakeSlice` | 14.04GB | 134/145 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 12.02GB | 133/145 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 11.92GB | 121/145 | `███░░░░░░░░░░░░ 20%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.91GB | 134/145 | `███░░░░░░░░░░░░ 20%` |

## Alerts

No anomalies detected.
