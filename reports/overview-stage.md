# Overview: stage
*Last updated: 2026-06-12 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T15:03 (1363 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,277 | avg: 14,201 | max: 28,205 | trend: stable (-0.29/hr))
```
▂▂▁▁▁▃▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▇▁▁▁▁▁▁▁▁▁▁▁▁▄▁▆▁▁▃▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▄▇▁█▇▁▁▁▁▁▂▁▁▁▁▁▃▁▂▅▃
```

**Heap InUse** (current: 184.4MB | avg: 162.0MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▃▅▅▆▂▄▃▇▅▆▁▆▆▁▅▃▂▄▃▁▁▄▂▁▄▂▄▅█▁▇▁▂▂▄▃▁▄▄▅▄▅▃▃▅▂▄▃▄▄▂▃▆▂▆▁▄▄▂▁▆▁▅▃▄▁▁▂▅▁▄▂▅▃▄▃▃▆▅▄▃▁▆▆▃▆▅▆▃▇▁▆▆▆▃▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,277 | 14,391 | -114 | 14,201 | 28,205 | stable (-0.29/hr) |
| Heap InUse | 184.4MB | 128.6MB | +55.8MB | 162.0MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1267.6MB | 1267.5MB | +0.1MB | 1180.3MB | 1805.8MB | |
| Heap Objects | 1,070,446 | 516,919 | +553527 | 881,761 | 2,707,946 | |

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
| 2026-06-12 | 31 | 14,163 | 149.1MB | 187.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `bytes.growSlice` | 2.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 34.41GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 20.1GB |
| 3 | `reflect.unsafe_NewArray` | 14.66GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 8.2GB |
| 5 | `reflect.MakeSlice` | 8.17GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.61GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.61GB |
| 8 | `database/sql.convertAssignRows` | 2.32GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.87GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.68GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 232.68MB | 223.39MB | 105.17MB | 0B |
| `evaluation.mergeMetadata` | 103.52MB | 100.52MB | 45.84MB | 0B |
| `local.(*Client).EvaluateV2` | 379.89MB | 358.55MB | 168.72MB | 0B |
| `local.topologicalSort` | 45.78MB | 40.72MB | 21.31MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 340.59MB | 323.41MB | 152.42MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 70.74MB | 66.06MB | 30.17MB | 0B |
| `localEvaluation.getMapOfValue` | 340.59MB | 323.41MB | 152.42MB | 0B |
| `utils.ParseFeatureFlag` | 342.09MB | 324.91MB | 153.34MB | 0B |

**Total FF alloc (current snapshot):** 1.81GB  |  **24h avg:** 829.39MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1361/1363 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1363 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1363 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 13.09MB | 1357/1363 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1363 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1363 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1363 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1363 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1358/1363 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1363 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.13GB | 1353/1363 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1363 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1363 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1363 | `█████████░░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.66GB | 1244/1363 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.74GB | 1352/1363 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1363 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1363 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.91GB | 1343/1363 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.12GB | 1240/1363 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
