# Overview: stage
*Last updated: 2026-05-16 04:27 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T04:27 (21 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,079 | avg: 14,141 | max: 14,425 | trend: decreasing (-3.03/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁▁▆▁▄▁▁
```

**Heap InUse** (current: 109.4MB | avg: 137.0MB | max: 181.5MB | trend: stable (-0.22MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁▆▁▂▇▆▂
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,079 | 14,065 | +14 | 14,141 | 14,425 | decreasing (-3.03/hr) |
| Heap InUse | 109.4MB | 168.4MB | -59.0MB | 137.0MB | 181.5MB | stable (-0.22MB/hr) |
| Heap Sys | 604.8MB | 607.6MB | -2.8MB | 326.9MB | 608.5MB | |
| Heap Objects | 424,050 | 1,192,810 | -768760 | 766,073 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 11 | 14,110 | 131.8MB | 169.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `encoding/json.(*decodeState).objectInterface` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.09GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 3.59GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 3.55GB |
| 4 | `internal/evaluation.mergeMetadata` | 3.52GB |
| 5 | `reflect.unsafe_NewArray` | 3.11GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.88GB |
| 7 | `experiment/local.topologicalSort` | 1.83GB |
| 8 | `reflect.MakeSlice` | 1.73GB |
| 9 | `segmentio/kafka-go.makeLayout` | 771.1MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 686.54MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 19/21 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 19/21 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.18MB | 11/21 | `███░░░░░░░░░░░░ 22%` |
| 4 | `runtime.mallocgc` | 5.85MB | 16/21 | `██░░░░░░░░░░░░░ 15%` |
| 5 | `segmentio/kafka-go.makePartitions` | 2.95MB | 10/21 | `█░░░░░░░░░░░░░░ 8%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 10/21 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 19/21 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.2MB | 17/21 | `░░░░░░░░░░░░░░░ 6%` |
| 9 | `aws/endpoints.init` | 2.0MB | 10/21 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `encoding/json.(*decodeState).objectInterface` | 2.0MB | 1/21 | `░░░░░░░░░░░░░░░ 5%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 2.69GB | 12/21 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 1.55GB | 8/21 | `████████░░░░░░░ 57%` |
| 3 | `reflect.unsafe_NewArray` | 1.17GB | 12/21 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 1.09GB | 13/21 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 1.02GB | 14/21 | `█████░░░░░░░░░░ 37%` |
| 6 | `reflect.MakeSlice` | 808.5MB | 10/21 | `███████████████ 100%` |
| 7 | `experiment/local.topologicalSort` | 732.34MB | 9/21 | `███████████████ 100%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 693.46MB | 10/21 | `███████████████ 100%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 578.91MB | 4/21 | `███████████████ 100%` |
| 10 | `segmentio/kafka-go.makeLayout` | 229.42MB | 15/21 | `███████████████ 100%` |

## Alerts

No anomalies detected.
