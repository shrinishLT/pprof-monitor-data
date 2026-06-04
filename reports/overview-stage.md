# Overview: stage
*Last updated: 2026-06-04 14:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:30 (980 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,194 | avg: 14,225 | max: 28,205 | trend: stable (-0.37/hr))
```
▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄▁▁▁▁▁▄▅▂
```

**Heap InUse** (current: 116.2MB | avg: 166.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂▁▃▅▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,194 | 14,581 | -387 | 14,225 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 116.2MB | 192.6MB | -76.4MB | 166.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 336.0MB | 313.4MB | +22.6MB | 1281.8MB | 1805.8MB | |
| Heap Objects | 529,423 | 920,288 | -390865 | 883,028 | 2,707,946 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 72 | 14,362 | 180.0MB | 556.9MB |
| 2026-05-22 | 50 | 14,165 | 186.1MB | 277.6MB |
| 2026-05-23 | 48 | 14,133 | 181.2MB | 368.1MB |
| 2026-05-24 | 48 | 14,127 | 179.7MB | 263.6MB |
| 2026-05-25 | 48 | 14,341 | 196.2MB | 338.8MB |
| 2026-05-26 | 46 | 14,155 | 171.1MB | 299.9MB |
| 2026-05-27 | 47 | 14,177 | 151.2MB | 232.3MB |
| 2026-05-28 | 48 | 14,161 | 148.6MB | 218.1MB |
| 2026-05-29 | 48 | 14,166 | 148.6MB | 258.2MB |
| 2026-05-30 | 48 | 14,205 | 164.1MB | 277.7MB |
| 2026-05-31 | 48 | 14,126 | 149.1MB | 213.6MB |
| 2026-06-01 | 48 | 14,226 | 160.1MB | 355.0MB |
| 2026-06-02 | 48 | 14,148 | 157.1MB | 206.0MB |
| 2026-06-03 | 48 | 14,147 | 154.2MB | 260.4MB |
| 2026-06-04 | 29 | 14,181 | 140.8MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `aws/endpoints.init` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `bufio.NewReaderSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 2.36GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 1.92GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 1.89GB |
| 4 | `internal/evaluation.mergeMetadata` | 1.79GB |
| 5 | `reflect.unsafe_NewArray` | 1022.41MB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1001.7MB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 985.45MB |
| 8 | `experiment/local.topologicalSort` | 964.1MB |
| 9 | `reflect.MakeSlice` | 567.01MB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 430.99MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.24GB | 3.25GB | 5.70GB | 0B |
| `evaluation.mergeMetadata` | 1.79GB | 1.37GB | 2.43GB | 0B |
| `local.(*Client).EvaluateV2` | 7.14GB | 5.51GB | 9.55GB | 0B |
| `local.topologicalSort` | 1009.60MB | 781.86MB | 1.31GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.11GB | 6.26GB | 10.85GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 20.32MB | 14.69MB | 17.74MB | 0B |
| `localEvaluation.getMapOfValue` | 8.11GB | 6.26GB | 10.85GB | 0B |
| `utils.ParseFeatureFlag` | 53.26MB | 37.25MB | 105.76MB | 0B |

**Total FF alloc (current snapshot):** 30.44GB  |  **24h avg:** 40.82GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 978/980 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/980 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/980 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.46MB | 974/980 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/980 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/980 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/980 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/980 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 975/980 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/980 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.55GB | 970/980 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.98GB | 320/980 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.3GB | 321/980 | `██████████░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.8GB | 315/980 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.37GB | 923/980 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.91GB | 969/980 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.32GB | 294/980 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.23GB | 300/980 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.05GB | 960/980 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.76GB | 920/980 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
