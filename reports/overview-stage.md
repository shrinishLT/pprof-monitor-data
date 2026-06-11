# Overview: stage
*Last updated: 2026-06-11 05:33 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T05:33 (1296 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,208 | avg: 14,204 | max: 28,205 | trend: stable (-0.30/hr))
```
▃█▃▁▁▁▁▁▁▁▁▁▁▁▄▁▄▁▁▁▂▁▁▁▁▃▂▂▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▃▃▁▂▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 199.7MB | avg: 163.0MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄█▄▂▄▃▄▄▂▃▂▂▂▃▃▂▃▁▄▃▄▂▂▂▄▁▃▂▃▃▂▃▃▂▂▃▃▃▃▂▂▁▃▂▂▂▂▃▁▃▃▃▂▄▄▃▃▂▃▂▂▂▂▂▂▇▃▂▃▃▃▁▂▂▄▃▃▁▃▃▁▃▂▁▂▂▁▁▃▂▁▃▁▃▃▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,208 | 14,081 | +127 | 14,204 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 199.7MB | 164.5MB | +35.2MB | 163.0MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 379.8MB | 381.0MB | -1.2MB | 1206.8MB | 1805.8MB | |
| Heap Objects | 1,450,200 | 1,111,268 | +338932 | 884,748 | 2,707,946 | |

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
| 2026-06-11 | 12 | 14,091 | 140.0MB | 199.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `kafka-go/protocol.newPage` | 1.6MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.15GB |
| 2 | `reflect.unsafe_NewArray` | 7.06GB |
| 3 | `reflect.MakeSlice` | 3.94GB |
| 4 | `segmentio/kafka-go.makeLayout` | 1.75GB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 970.26MB |
| 6 | `internal/reflectlite.unsafe_New` | 832.58MB |
| 7 | `v3/newrelic.newLogEvents` | 553.56MB |
| 8 | `compress/flate.NewWriter` | 527.98MB |
| 9 | `kafka-go/protocol.bytesToString` | 433.52MB |
| 10 | `io.ReadAll` | 427.46MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 80.45MB | 73.83MB | 800.71MB | 0B |
| `evaluation.mergeMetadata` | 37.51MB | 33.51MB | 339.19MB | 0B |
| `local.(*Client).EvaluateV2` | 138.20MB | 126.35MB | 1.33GB | 0B |
| `local.topologicalSort` | 20.84MB | 18.81MB | 196.36MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 145.84MB | 133.47MB | 1.38GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 9.94MB | 9.94MB | 133.44MB | 0B |
| `localEvaluation.getMapOfValue` | 145.84MB | 133.47MB | 1.38GB | 0B |
| `utils.ParseFeatureFlag` | 145.84MB | 133.47MB | 1.38GB | 0B |

**Total FF alloc (current snapshot):** 724.44MB  |  **24h avg:** 6.90GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1294/1296 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.67MB | 49/1296 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1296 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.3MB | 1290/1296 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 51/1296 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1296 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1296 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1296 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1291/1296 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1296 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.25GB | 1286/1296 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1296 | `█████████░░░░░░ 64%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1296 | `█████████░░░░░░ 64%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1296 | `█████████░░░░░░ 63%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.91GB | 1205/1296 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.53GB | 1285/1296 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1296 | `█████░░░░░░░░░░ 34%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1296 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 23.92GB | 1276/1296 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.66GB | 1202/1296 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
