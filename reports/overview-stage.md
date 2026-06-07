# Overview: stage
*Last updated: 2026-06-07 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T18:02 (1130 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,089 | avg: 14,212 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▄▂▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▅▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 188.5MB | avg: 164.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▁▂▃▂▃▁▂▁▁▁▃▁▃▂▃▁▂▁▁▃▁▁▅▂▂▁▁▁▂▂▃▂▁▁▂▃▁▁▂▁▃▃▃▃▁▂▂▁▂▂▂▃▃▂▂▁▃▁▁▃▂▃▁▂▁▂▁▃▃▁▆█▁▃▄▂▃▁▂▁▂▃▃▁▃▃▁▃▃▃▂▁▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,089 | 14,073 | +16 | 14,212 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 188.5MB | 162.1MB | +26.4MB | 164.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1097.4MB | 1097.5MB | -0.1MB | 1228.3MB | 1805.8MB | |
| Heap Objects | 1,345,742 | 1,104,058 | +241684 | 882,001 | 2,707,946 | |

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
| 2026-06-04 | 47 | 14,166 | 140.9MB | 258.6MB |
| 2026-06-05 | 48 | 14,143 | 157.3MB | 338.5MB |
| 2026-06-06 | 48 | 14,125 | 145.8MB | 231.1MB |
| 2026-06-07 | 36 | 14,110 | 159.5MB | 298.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `reflect.unsafe_NewArray` | 1.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 117.84GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 56.38GB |
| 3 | `reflect.unsafe_NewArray` | 51.1GB |
| 4 | `reflect.MakeSlice` | 28.64GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 22.09GB |
| 6 | `segmentio/kafka-go.makeLayout` | 12.62GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.02GB |
| 8 | `database/sql.convertAssignRows` | 6.22GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.13GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 685.42MB | 679.33MB | 589.08MB | 0B |
| `evaluation.mergeMetadata` | 294.57MB | 290.57MB | 251.18MB | 0B |
| `local.(*Client).EvaluateV2` | 1.15GB | 1.14GB | 1017.36MB | 0B |
| `local.topologicalSort` | 175.97MB | 173.43MB | 155.42MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.18GB | 1.17GB | 1.01GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 122.74MB | 121.16MB | 107.15MB | 0B |
| `localEvaluation.getMapOfValue` | 1.18GB | 1.17GB | 1.01GB | 0B |
| `utils.ParseFeatureFlag` | 1.18GB | 1.17GB | 1.01GB | 0B |

**Total FF alloc (current snapshot):** 5.94GB  |  **24h avg:** 5.11GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1128/1130 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.49MB | 45/1130 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.42MB | 29/1130 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.37MB | 1124/1130 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.76MB | 47/1130 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1130 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1130 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1130 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1125/1130 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1130 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.8GB | 1120/1130 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1130 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1130 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1130 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.5GB | 1060/1130 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 38.43GB | 1119/1130 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1130 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1130 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 21.64GB | 1110/1130 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 1057/1130 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
