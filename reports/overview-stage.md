# Overview: stage
*Last updated: 2026-06-10 09:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T09:32 (1257 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,207 | max: 28,205 | trend: stable (-0.30/hr))
```
▁▂▁▁▁▁▂▁▃▁▃▁▁▁▁█▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▃▁▁▁▁▁▁
```

**Heap InUse** (current: 173.6MB | avg: 163.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▃▂▁▄▂▂▁▄▂▃▃▂▄▂▃▂▄▃▁▁▁▃▁▃▁▁▂▁▃▃▄▂▃▄▃▁▁▁▄█▃▂▄▃▄▄▂▃▂▂▂▃▂▂▂▁▄▃▄▁▂▂▄▁▃▂▃▃▂▃▃▂▂▂▃▃▂▂▁▁▂▂▂▂▂▃▁▃▂▂▂▃▄▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,078 | -5 | 14,207 | 28,205 | stable (-0.30/hr) |
| Heap InUse | 173.6MB | 165.8MB | +7.8MB | 163.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1262.8MB | 1262.8MB | +0.0MB | 1221.4MB | 1805.8MB | |
| Heap Objects | 1,226,432 | 1,045,973 | +180459 | 885,920 | 2,707,946 | |

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
| 2026-06-10 | 20 | 14,144 | 152.0MB | 184.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.1MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `reflect.unsafe_NewArray` | 3.51MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 233.58GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 111.46GB |
| 3 | `reflect.unsafe_NewArray` | 100.96GB |
| 4 | `reflect.MakeSlice` | 56.44GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 43.83GB |
| 6 | `segmentio/kafka-go.makeLayout` | 24.93GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 13.96GB |
| 8 | `database/sql.convertAssignRows` | 12.42GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 11.94GB |
| 10 | `internal/reflectlite.unsafe_New` | 11.36GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.33GB | 1.33GB | 1.22GB | 0B |
| `evaluation.mergeMetadata` | 575.14MB | 574.64MB | 528.75MB | 0B |
| `local.(*Client).EvaluateV2` | 2.27GB | 2.27GB | 2.08GB | 0B |
| `local.topologicalSort` | 335.44MB | 334.43MB | 310.58MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.35GB | 2.35GB | 2.15GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 227.13MB | 227.13MB | 211.22MB | 0B |
| `localEvaluation.getMapOfValue` | 2.35GB | 2.35GB | 2.15GB | 0B |
| `utils.ParseFeatureFlag` | 2.35GB | 2.35GB | 2.16GB | 0B |

**Total FF alloc (current snapshot):** 11.78GB  |  **24h avg:** 10.79GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1255/1257 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.26MB | 48/1257 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.15MB | 31/1257 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.35MB | 1251/1257 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 11.61MB | 50/1257 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/1257 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/1257 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/1257 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 1252/1257 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/1257 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.69GB | 1247/1257 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 63.79GB | 321/1257 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.11GB | 322/1257 | `█████████░░░░░░ 64%` |
| 4 | `internal/evaluation.mergeMetadata` | 62.61GB | 316/1257 | `█████████░░░░░░ 64%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.99GB | 1187/1257 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.29GB | 1246/1257 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.21GB | 295/1257 | `█████░░░░░░░░░░ 35%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.13GB | 301/1257 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 23.79GB | 1237/1257 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.34GB | 1184/1257 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
