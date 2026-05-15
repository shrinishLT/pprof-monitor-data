# Overview: stage
*Last updated: 2026-05-16 01:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T01:03 (15 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,138 | max: 14,425 | trend: decreasing (-9.49/hr))
```
▁▂▁▁▁█▇▄▁▃▁▁▁▁▁
```

**Heap InUse** (current: 99.1MB | avg: 137.2MB | max: 181.5MB | trend: stable (-0.32MB/hr))
```
▃▅▁▇▄▄▃▄▆█▁▃▆▆▁
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██████░░░░░░░░░░░░░░ 31%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,074 | -3 | 14,138 | 14,425 | decreasing (-9.49/hr) |
| Heap InUse | 99.1MB | 156.8MB | -57.7MB | 137.2MB | 181.5MB | stable (-0.32MB/hr) |
| Heap Sys | 188.9MB | 189.1MB | -0.2MB | 270.3MB | 318.0MB | |
| Heap Objects | 391,212 | 1,125,781 | -734569 | 773,224 | 1,309,284 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 5 | 14,066 | 126.2MB | 161.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.77GB |
| 2 | `reflect.unsafe_NewArray` | 781.4MB |
| 3 | `reflect.MakeSlice` | 444.01MB |
| 4 | `segmentio/kafka-go.makeLayout` | 172.85MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 122.33MB |
| 6 | `internal/evaluation.mergeMetadata` | 94.52MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 93.53MB |
| 8 | `internal/reflectlite.unsafe_New` | 88.51MB |
| 9 | `compress/flate.NewWriter` | 85.5MB |
| 10 | `internal/evaluation.(*Engine).Evaluate` | 84.3MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 13/15 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.19MB | 13/15 | `███░░░░░░░░░░░░ 25%` |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 7.2MB | 5/15 | `██░░░░░░░░░░░░░ 19%` |
| 4 | `runtime.mallocgc` | 3.01MB | 10/15 | `█░░░░░░░░░░░░░░ 8%` |
| 5 | `segmentio/kafka-go.makePartitions` | 2.61MB | 5/15 | `█░░░░░░░░░░░░░░ 7%` |
| 6 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.5MB | 4/15 | `█░░░░░░░░░░░░░░ 6%` |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.3MB | 13/15 | `░░░░░░░░░░░░░░░ 6%` |
| 8 | `compress/flate.NewWriter` | 2.02MB | 12/15 | `░░░░░░░░░░░░░░░ 5%` |
| 9 | `aws/endpoints.init` | 2.0MB | 4/15 | `░░░░░░░░░░░░░░░ 5%` |
| 10 | `reflect.unsafe_NewArray` | 709.46kB | 6/15 | `███████████████ 100%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 802.48MB | 6/15 | `███████████████ 100%` |
| 2 | `reflect.unsafe_NewArray` | 342.8MB | 6/15 | `██████░░░░░░░░░ 42%` |
| 3 | `reflect.MakeSlice` | 302.26MB | 4/15 | `█████░░░░░░░░░░ 37%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 264.66MB | 7/15 | `████░░░░░░░░░░░ 32%` |
| 5 | `experiment/local.(*Client).EvaluateV2` | 233.76MB | 8/15 | `████░░░░░░░░░░░ 29%` |
| 6 | `compress/flate.NewWriter` | 96.93MB | 13/15 | `█░░░░░░░░░░░░░░ 12%` |
| 7 | `internal/evaluation.mergeMetadata` | 79.52MB | 2/15 | `█░░░░░░░░░░░░░░ 9%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 70.33MB | 6/15 | `█░░░░░░░░░░░░░░ 8%` |
| 9 | `internal/reflectlite.unsafe_New` | 56.63MB | 4/15 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `segmentio/kafka-go.makeLayout` | 55.68MB | 9/15 | `█░░░░░░░░░░░░░░ 6%` |

## Alerts

No anomalies detected.
