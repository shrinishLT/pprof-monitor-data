# Overview: stage
*Last updated: 2026-05-16 02:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T02:31 (18 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,141 | max: 14,425 | trend: decreasing (-3.54/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆▁
```

**Heap InUse** (current: 106.6MB | avg: 135.0MB | max: 181.5MB | trend: decreasing (-1.68MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁▆▁▂
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,344 | -277 | 14,141 | 14,425 | decreasing (-3.54/hr) |
| Heap InUse | 106.6MB | 102.2MB | +4.4MB | 135.0MB | 181.5MB | decreasing (-1.68MB/hr) |
| Heap Sys | 608.0MB | 192.9MB | +415.1MB | 280.2MB | 608.0MB | |
| Heap Objects | 393,321 | 300,456 | +92865 | 748,952 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 8 | 14,100 | 125.2MB | 162.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.06GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 2.59GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 2.54GB |
| 4 | `internal/evaluation.mergeMetadata` | 2.54GB |
| 5 | `reflect.unsafe_NewArray` | 1.76GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.37GB |
| 7 | `experiment/local.topologicalSort` | 1.33GB |
| 8 | `reflect.MakeSlice` | 1015.52MB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 504.53MB |
| 10 | `segmentio/kafka-go.makeLayout` | 429.25MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 16/18 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 16/18 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 7.88MB | 8/18 | `███░░░░░░░░░░░░ 21%` |
| 4 | `runtime.mallocgc` | 4.4MB | 13/18 | `█░░░░░░░░░░░░░░ 12%` |
| 5 | `segmentio/kafka-go.makePartitions` | 2.86MB | 7/18 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 7/18 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 16/18 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.15MB | 15/18 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `aws/endpoints.init` | 2.0MB | 7/18 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `bytes.growSlice` | 1.51MB | 1/18 | `░░░░░░░░░░░░░░░ 4%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 1.63GB | 9/18 | `███████████████ 100%` |
| 2 | `reflect.unsafe_NewArray` | 717.78MB | 9/18 | `███████████████ 100%` |
| 3 | `internal/evaluation.mergeMetadata` | 624.62MB | 5/18 | `███████████████ 100%` |
| 4 | `reflect.MakeSlice` | 527.44MB | 7/18 | `███████████████ 100%` |
| 5 | `internal/evaluation.(*Engine).evaluateFlag` | 504.53MB | 1/18 | `███████████████ 100%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 479.78MB | 10/18 | `███████████████ 100%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 443.24MB | 11/18 | `███████████████ 100%` |
| 8 | `experiment/local.topologicalSort` | 265.66MB | 6/18 | `███████████████ 100%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 260.69MB | 7/18 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makeLayout` | 128.4MB | 12/18 | `███████████████ 100%` |

## Alerts

No anomalies detected.
