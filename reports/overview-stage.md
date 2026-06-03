# Overview: stage
*Last updated: 2026-06-04 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T05:00 (961 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,089 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁
```

**Heap InUse** (current: 126.5MB | avg: 166.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▁▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,089 | 14,211 | -122 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 126.5MB | 142.8MB | -16.3MB | 166.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 212.7MB | 212.7MB | +0.0MB | 1294.3MB | 1805.8MB | |
| Heap Objects | 710,830 | 831,936 | -121106 | 885,537 | 2,707,946 | |

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
| 2026-06-04 | 10 | 14,118 | 131.7MB | 161.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 4.41MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `compress/flate.(*compressor).initDeflate` | 2.67MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 2.45GB |
| 2 | `reflect.unsafe_NewArray` | 1.04GB |
| 3 | `reflect.MakeSlice` | 578.01MB |
| 4 | `segmentio/kafka-go.makeLayout` | 268.52MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 137.62MB |
| 6 | `internal/reflectlite.unsafe_New` | 129.01MB |
| 7 | `compress/flate.NewWriter` | 112.82MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 105.11MB |
| 9 | `experiment/local.(*Client).EvaluateV2` | 96.54MB |
| 10 | `internal/evaluation.mergeMetadata` | 94.52MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 230.13MB | 228.09MB | 6.23GB | 0B |
| `evaluation.mergeMetadata` | 94.52MB | 94.02MB | 2.68GB | 0B |
| `local.(*Client).EvaluateV2` | 383.08MB | 379.99MB | 10.39GB | 0B |
| `local.topologicalSort` | 56.41MB | 55.90MB | 1.41GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 428.98MB | 425.37MB | 11.79GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 23.46MB | 0B |
| `localEvaluation.getMapOfValue` | 428.98MB | 425.37MB | 11.79GB | 0B |
| `utils.ParseFeatureFlag` | 18.04MB | 18.04MB | 110.48MB | 0B |

**Total FF alloc (current snapshot):** 1.60GB  |  **24h avg:** 44.42GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 959/961 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/961 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/961 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.54MB | 955/961 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/961 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/961 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/961 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/961 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 957/961 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/961 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.18GB | 952/961 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.2GB | 304/961 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 66.91GB | 303/961 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 66.24GB | 298/961 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.0GB | 908/961 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.62GB | 951/961 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.68GB | 296/961 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 34.67GB | 291/961 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.43GB | 943/961 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.01GB | 906/961 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
