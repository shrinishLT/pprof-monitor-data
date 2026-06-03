# Overview: stage
*Last updated: 2026-06-04 04:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T04:00 (959 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,273 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 160.3MB | avg: 166.6MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▂▄▁▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,273 | 14,109 | +164 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 160.3MB | 161.6MB | -1.3MB | 166.6MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 214.1MB | 185.7MB | +28.4MB | 1296.6MB | 1805.8MB | |
| Heap Objects | 1,052,747 | 920,181 | +132566 | 885,775 | 2,707,946 | |

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
| 2026-06-04 | 8 | 14,110 | 131.0MB | 161.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bytes.growSlice` | 2.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `bufio.NewReaderSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 852.57MB |
| 2 | `reflect.unsafe_NewArray` | 370.95MB |
| 3 | `reflect.MakeSlice` | 204.5MB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 101.39MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 93.36MB |
| 6 | `internal/evaluation.mergeMetadata` | 89.52MB |
| 7 | `segmentio/kafka-go.makeLayout` | 83.9MB |
| 8 | `compress/flate.NewWriter` | 66.11MB |
| 9 | `experiment/local.topologicalSort` | 51.37MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 45.71MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 219.41MB | 83.83MB | 7.57GB | 0B |
| `evaluation.mergeMetadata` | 89.52MB | 30.51MB | 3.25GB | 0B |
| `local.(*Client).EvaluateV2` | 367.65MB | 146.67MB | 12.61GB | 0B |
| `local.topologicalSort` | 54.87MB | 24.40MB | 1.72GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 413.02MB | 168.30MB | 14.31GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 28.67MB | 0B |
| `localEvaluation.getMapOfValue` | 413.02MB | 168.30MB | 14.31GB | 0B |
| `utils.ParseFeatureFlag` | 9.86MB | 3.13MB | 131.03MB | 0B |

**Total FF alloc (current snapshot):** 1.53GB  |  **24h avg:** 53.93GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 957/959 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/959 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/959 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.55MB | 953/959 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/959 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/959 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/959 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/959 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 955/959 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/959 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.38GB | 950/959 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.65GB | 302/959 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.36GB | 301/959 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 66.68GB | 296/959 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.0GB | 908/959 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 41.71GB | 949/959 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.68GB | 296/959 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 34.67GB | 291/959 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 23.48GB | 941/959 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.01GB | 906/959 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
