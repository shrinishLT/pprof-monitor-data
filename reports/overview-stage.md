# Overview: stage
*Last updated: 2026-06-04 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T05:31 (962 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,075 | avg: 14,225 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁
```

**Heap InUse** (current: 140.8MB | avg: 166.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▄▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,075 | 14,089 | -14 | 14,225 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 140.8MB | 126.5MB | +14.3MB | 166.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 211.6MB | 212.7MB | -1.1MB | 1293.2MB | 1805.8MB | |
| Heap Objects | 861,853 | 710,830 | +151023 | 885,512 | 2,707,946 | |

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
| 2026-06-04 | 11 | 14,114 | 132.5MB | 161.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 3.26GB |
| 2 | `reflect.unsafe_NewArray` | 1.39GB |
| 3 | `reflect.MakeSlice` | 770.52MB |
| 4 | `segmentio/kafka-go.makeLayout` | 362.67MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 188.04MB |
| 6 | `internal/reflectlite.unsafe_New` | 164.52MB |
| 7 | `compress/flate.NewWriter` | 143.67MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 111.46MB |
| 9 | `v3/newrelic.newLogEvents` | 109.84MB |
| 10 | `internal/evaluation.mergeMetadata` | 101.52MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 244.49MB | 230.13MB | 5.73GB | 0B |
| `evaluation.mergeMetadata` | 101.52MB | 94.52MB | 2.46GB | 0B |
| `local.(*Client).EvaluateV2` | 404.74MB | 383.08MB | 9.56GB | 0B |
| `local.topologicalSort` | 59.46MB | 56.41MB | 1.30GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 452.71MB | 428.98MB | 10.84GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 0B | 21.50MB | 0B |
| `localEvaluation.getMapOfValue` | 452.71MB | 428.98MB | 10.84GB | 0B |
| `utils.ParseFeatureFlag` | 28.32MB | 18.04MB | 103.64MB | 0B |

**Total FF alloc (current snapshot):** 1.70GB  |  **24h avg:** 40.86GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 960/962 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/962 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/962 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.54MB | 956/962 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/962 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/962 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/962 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/962 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 958/962 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/962 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.09GB | 953/962 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.2GB | 304/962 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 66.69GB | 304/962 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 66.01GB | 299/962 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.0GB | 908/962 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.58GB | 952/962 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.68GB | 296/962 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 34.67GB | 291/962 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.41GB | 944/962 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.01GB | 906/962 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
