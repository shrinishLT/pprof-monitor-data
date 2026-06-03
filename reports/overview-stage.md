# Overview: stage
*Last updated: 2026-06-04 02:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T02:02 (955 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 100.0MB | avg: 166.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▃▄▁▂▄▁▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,076 | -10 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 100.0MB | 157.0MB | -57.0MB | 166.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 895.8MB | 895.6MB | +0.2MB | 1299.7MB | 1805.8MB | |
| Heap Objects | 339,658 | 1,055,270 | -715612 | 886,076 | 2,707,946 | |

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
| 2026-06-04 | 4 | 14,087 | 116.7MB | 157.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.58MB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 6 | `aws/endpoints.init` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.69GB |
| 2 | `segmentio/kafka-go.makePartitions` | 11.29GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.62GB |
| 4 | `reflect.unsafe_NewArray` | 4.97GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 4.43GB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 4.43GB |
| 7 | `internal/evaluation.mergeMetadata` | 4.35GB |
| 8 | `reflect.MakeSlice` | 2.77GB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.3GB |
| 10 | `experiment/local.topologicalSort` | 2.2GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.13GB | 10.11GB | 9.49GB | 0B |
| `evaluation.mergeMetadata` | 4.35GB | 4.34GB | 4.08GB | 0B |
| `local.(*Client).EvaluateV2` | 16.90GB | 16.86GB | 15.81GB | 0B |
| `local.topologicalSort` | 2.30GB | 2.29GB | 2.15GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 19.18GB | 19.13GB | 17.95GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 41.45MB | 39.90MB | 35.03MB | 0B |
| `localEvaluation.getMapOfValue` | 19.18GB | 19.13GB | 17.95GB | 0B |
| `utils.ParseFeatureFlag` | 174.20MB | 170.04MB | 153.57MB | 0B |

**Total FF alloc (current snapshot):** 72.26GB  |  **24h avg:** 67.60GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 953/955 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/955 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/955 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.57MB | 949/955 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/955 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/955 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/955 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/955 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 951/955 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/955 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.76GB | 946/955 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.53GB | 298/955 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.23GB | 297/955 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 67.57GB | 292/955 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.08GB | 906/955 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.87GB | 945/955 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 35.13GB | 287/955 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.02GB | 293/955 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.58GB | 937/955 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.05GB | 904/955 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
