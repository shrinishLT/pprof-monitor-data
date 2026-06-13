# Overview: stage
*Last updated: 2026-06-13 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T06:31 (1394 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,849 | avg: 14,199 | max: 28,205 | trend: stable (-0.28/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▃▄▁▅▅▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁█
```

**Heap InUse** (current: 214.7MB | avg: 161.7MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▂▁▃▂▁▃▄▅▃▄▂▂▄▂▄▃▄▄▂▂▅▂▅▁▃▃▂▁▅▁▄▂▄▁▁▂▅▁▄▂▅▂▃▃▃▅▅▃▂▁▅▅▃▅▄▆▃▆▁▅▅▆▂▆▂▄▄▅▃▁▆▁▅▆▃▆▂▁▅▃▃▄▃▃▅▃▁▁▆▆▂▂▂▁█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,849 | 14,067 | +782 | 14,199 | 28,205 | stable (-0.28/hr) |
| Heap InUse | 214.7MB | 106.2MB | +108.5MB | 161.7MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1264.8MB | 1268.5MB | -3.7MB | 1182.3MB | 1805.8MB | |
| Heap Objects | 1,275,107 | 335,764 | +939343 | 880,679 | 2,707,946 | |

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
| 2026-06-13 | 14 | 14,150 | 144.1MB | 214.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bytes.growSlice` | 6.53MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `reflect.mapassign_faststr0` | 4.0MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 62.69GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 35.53GB |
| 3 | `reflect.unsafe_NewArray` | 26.93GB |
| 4 | `reflect.MakeSlice` | 14.94GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.55GB |
| 6 | `segmentio/kafka-go.makeLayout` | 6.61GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.56GB |
| 8 | `database/sql.convertAssignRows` | 4.08GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.31GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.04GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 381.45MB | 354.90MB | 267.76MB | 0B |
| `evaluation.mergeMetadata` | 168.54MB | 155.04MB | 117.65MB | 0B |
| `local.(*Client).EvaluateV2` | 627.40MB | 588.86MB | 438.95MB | 0B |
| `local.topologicalSort` | 73.19MB | 68.63MB | 51.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 585.78MB | 551.34MB | 402.85MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 102.95MB | 93.70MB | 75.84MB | 0B |
| `localEvaluation.getMapOfValue` | 585.78MB | 551.34MB | 402.85MB | 0B |
| `utils.ParseFeatureFlag` | 587.28MB | 552.84MB | 404.34MB | 0B |

**Total FF alloc (current snapshot):** 3.04GB  |  **24h avg:** 2.11GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1392/1394 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76MB | 52/1394 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.77MB | 32/1394 | `██████░░░░░░░░░ 43%` |
| 4 | `runtime.mallocgc` | 13.01MB | 1388/1394 | `█████░░░░░░░░░░ 35%` |
| 5 | `database/sql.convertAssignRows` | 11.45MB | 54/1394 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1394 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1394 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1394 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1389/1394 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1394 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.12GB | 1384/1394 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1394 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1394 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1394 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.96GB | 1275/1394 | `████████░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 40.29GB | 1383/1394 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1394 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1394 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 22.66GB | 1374/1394 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.8GB | 1271/1394 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
