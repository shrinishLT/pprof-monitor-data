# Overview: stage
*Last updated: 2026-06-04 00:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:32 (953 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,099 | avg: 14,226 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 103.8MB | avg: 166.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▃▂▂▃▄▁▂▄▁▄▄▃▃▃▃▁▃▄▁▂▂▂▂▃▃▄▃▁▅▃▂▃▂▃▄▃▃▄▄▄▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▁▁▂▁▃▂▄▂▃▄▁▄▁▂▁▁▄▃▂▂▄▃▂▂█▄▁▄▄▃▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,099 | 14,106 | -7 | 14,226 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 103.8MB | 106.1MB | -2.3MB | 166.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 899.0MB | 899.0MB | +0.0MB | 1300.6MB | 1805.8MB | |
| Heap Objects | 333,666 | 334,137 | -471 | 886,472 | 2,707,946 | |

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
| 2026-06-04 | 2 | 14,102 | 104.9MB | 106.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `aws/endpoints.init` | 2.5MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.67GB |
| 2 | `segmentio/kafka-go.makePartitions` | 8.6GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.13GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 4.18GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 4.18GB |
| 6 | `internal/evaluation.mergeMetadata` | 4.13GB |
| 7 | `reflect.unsafe_NewArray` | 3.82GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.18GB |
| 9 | `reflect.MakeSlice` | 2.12GB |
| 10 | `experiment/local.topologicalSort` | 2.08GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.59GB | 9.36GB | 9.06GB | 512.14kB |
| `evaluation.mergeMetadata` | 4.13GB | 4.02GB | 3.90GB | 512.14kB |
| `local.(*Client).EvaluateV2` | 15.98GB | 15.60GB | 15.10GB | 1.04MB |
| `local.topologicalSort` | 2.18GB | 2.12GB | 2.05GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 18.14GB | 17.71GB | 17.14GB | 1.56MB |
| `localEvaluation.GetFeatureFlagPayload` | 34.70MB | 32.66MB | 31.27MB | 0B |
| `localEvaluation.getMapOfValue` | 18.14GB | 17.71GB | 17.14GB | 1.56MB |
| `utils.ParseFeatureFlag` | 151.90MB | 142.62MB | 141.20MB | 0B |

**Total FF alloc (current snapshot):** 68.34GB  |  **24h avg:** 64.56GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 951/953 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/953 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/953 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.59MB | 947/953 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/953 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/953 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/953 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/953 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 949/953 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/953 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.95GB | 944/953 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.96GB | 296/953 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.67GB | 295/953 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 68.0GB | 290/953 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.17GB | 904/953 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.95GB | 943/953 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 35.36GB | 285/953 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.25GB | 291/953 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.62GB | 935/953 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.08GB | 902/953 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
