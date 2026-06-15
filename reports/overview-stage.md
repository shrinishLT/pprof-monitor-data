# Overview: stage
*Last updated: 2026-06-15 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T23:31 (1524 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,196 | max: 28,205 | trend: stable (-0.24/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▇█▆▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 160.5MB | avg: 160.8MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▃▃▂▄▂▃▂▄▅▃▃█▄▄▂▂▃▁▄▁▂▁▄▂▁▄▁▄▁▁▂▃▄▄▂▂▄▃▁▂▃▂▅▄▂▃▃▂▂▃▂▃▆▄▄▂▂▄▂▄▇▂▅▂▂▃▁▃▄▁▅▂▂▅▄▄▁▂▄▂▄▂▆▆▄▁▁▂▃▂▄▁▁▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,066 | +10 | 14,196 | 28,205 | stable (-0.24/hr) |
| Heap InUse | 160.5MB | 133.6MB | +26.9MB | 160.8MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 291.3MB | 291.8MB | -0.5MB | 1178.3MB | 1805.8MB | |
| Heap Objects | 1,123,381 | 728,805 | +394576 | 878,867 | 2,707,946 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 3 | `runtime.mallocgc` | 7.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 1.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.57GB |
| 2 | `reflect.unsafe_NewArray` | 3.73GB |
| 3 | `reflect.MakeSlice` | 2.08GB |
| 4 | `segmentio/kafka-go.makeLayout` | 977.41MB |
| 5 | `fmt.Sprintf` | 537.58MB |
| 6 | `v3/newrelic.newAnalyticsEvents` | 519.34MB |
| 7 | `internal/reflectlite.unsafe_New` | 434.04MB |
| 8 | `compress/flate.NewWriter` | 340.23MB |
| 9 | `v3/newrelic.newLogEvents` | 284.0MB |
| 10 | `strconv.appendQuotedWith` | 261.76MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 79.04MB | 73.87MB | 423.39MB | 0B |
| `evaluation.mergeMetadata` | 30.01MB | 28.51MB | 186.08MB | 0B |
| `local.(*Client).EvaluateV2` | 131.26MB | 120.34MB | 699.33MB | 0B |
| `local.topologicalSort` | 19.32MB | 17.29MB | 88.38MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 138.01MB | 127.10MB | 699.39MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 11.81MB | 11.81MB | 81.14MB | 0B |
| `localEvaluation.getMapOfValue` | 138.01MB | 127.10MB | 699.39MB | 0B |
| `utils.ParseFeatureFlag` | 138.01MB | 127.10MB | 700.66MB | 0B |

**Total FF alloc (current snapshot):** 685.48MB  |  **24h avg:** 3.49GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1522/1524 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77MB | 56/1524 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.47MB | 35/1524 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 12.75MB | 1518/1524 | `█████░░░░░░░░░░ 34%` |
| 5 | `database/sql.convertAssignRows` | 11.44MB | 58/1524 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1524 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1524 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1524 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 1519/1524 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1524 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.3GB | 1514/1524 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1524 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1524 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1524 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.95GB | 1394/1524 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.34GB | 1513/1524 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1524 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1524 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.67GB | 1504/1524 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.68GB | 1390/1524 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.5x avg)
