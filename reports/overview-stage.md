# Overview: stage
*Last updated: 2026-06-17 02:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T02:02 (1576 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,650 | avg: 14,194 | max: 28,205 | trend: stable (-0.23/hr))
```
▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▇█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 157.6MB | avg: 160.2MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▆▄▄▂▃▄▂▄█▂▅▂▃▄▂▄▅▁▅▂▂▅▄▄▁▂▄▂▄▂▆▆▅▁▁▂▃▃▅▁▂▂▄▃▂▁▂▂▁▄▂▅▄▅▂▂▇▃▄▁▁▄▂▃▅▁▃▄▄▄▃▂▂▂▂▁▁▂▄▂▁▁▁▄▃▂▅▄▃▁▄▁▁▄▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,650 | 14,065 | +585 | 14,194 | 28,205 | stable (-0.23/hr) |
| Heap InUse | 157.6MB | 174.1MB | -16.5MB | 160.2MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 433.5MB | 434.7MB | -1.2MB | 1164.2MB | 1805.8MB | |
| Heap Objects | 840,785 | 1,313,959 | -473174 | 876,984 | 2,707,946 | |

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
| 2026-06-07 | 47 | 14,103 | 158.2MB | 298.5MB |
| 2026-06-08 | 48 | 14,210 | 154.6MB | 265.6MB |
| 2026-06-09 | 48 | 14,154 | 161.0MB | 283.6MB |
| 2026-06-10 | 47 | 14,121 | 151.2MB | 275.7MB |
| 2026-06-11 | 48 | 14,109 | 139.5MB | 199.7MB |
| 2026-06-12 | 48 | 14,135 | 148.8MB | 189.5MB |
| 2026-06-13 | 48 | 14,121 | 146.0MB | 214.7MB |
| 2026-06-14 | 48 | 14,120 | 150.8MB | 247.1MB |
| 2026-06-15 | 48 | 14,245 | 154.3MB | 238.3MB |
| 2026-06-16 | 47 | 14,139 | 142.5MB | 226.4MB |
| 2026-06-17 | 5 | 14,183 | 142.1MB | 174.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 17.35GB |
| 2 | `reflect.unsafe_NewArray` | 7.49GB |
| 3 | `reflect.MakeSlice` | 4.24GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 1.96GB |
| 5 | `segmentio/kafka-go.makeLayout` | 1.9GB |
| 6 | `v3/newrelic.newAnalyticsEvents` | 1.02GB |
| 7 | `internal/reflectlite.unsafe_New` | 846.58MB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 816.48MB |
| 9 | `compress/flate.NewWriter` | 562.35MB |
| 10 | `v3/newrelic.newLogEvents` | 545.56MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 134.43MB | 128.88MB | 102.92MB | 0B |
| `evaluation.mergeMetadata` | 64.52MB | 60.01MB | 42.74MB | 0B |
| `local.(*Client).EvaluateV2` | 226.60MB | 218.43MB | 175.23MB | 0B |
| `local.topologicalSort` | 30.88MB | 30.37MB | 23.83MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 224.91MB | 213.62MB | 176.50MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 31.07MB | 31.07MB | 20.92MB | 0B |
| `localEvaluation.getMapOfValue` | 224.91MB | 213.62MB | 176.50MB | 0B |
| `utils.ParseFeatureFlag` | 225.41MB | 214.13MB | 176.72MB | 0B |

**Total FF alloc (current snapshot):** 1.14GB  |  **24h avg:** 895.35MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1574/1576 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77MB | 56/1576 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1576 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.57MB | 1570/1576 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 58/1576 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1576 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1576 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1576 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.21MB | 1571/1576 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1576 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.69GB | 1566/1576 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1576 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1576 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1576 | `██████████░░░░░ 69%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.75GB | 1433/1576 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 39.21GB | 1565/1576 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1576 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1576 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 22.03GB | 1556/1576 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.16GB | 1429/1576 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (4.0x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
