# Overview: stage
*Last updated: 2026-06-04 06:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T06:32 (964 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,541 | avg: 14,225 | max: 28,205 | trend: stable (-0.38/hr))
```
▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅
```

**Heap InUse** (current: 258.6MB | avg: 166.5MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▅▃▃▃▃▁▃▄▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▁▂▅▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▁▂▃▃▂▂▂▁▇
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,541 | 14,104 | +437 | 14,225 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 258.6MB | 104.0MB | +154.6MB | 166.5MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 837.3MB | 215.5MB | +621.8MB | 1291.6MB | 1805.8MB | |
| Heap Objects | 982,502 | 440,147 | +542355 | 885,151 | 2,707,946 | |

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
| 2026-06-04 | 13 | 14,146 | 140.0MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.84MB |
| 3 | `runtime.mallocgc` | 10.51MB |
| 4 | `database/sql.convertAssignRows` | 9.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bytes.growSlice` | 4.52MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 2.55MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 10.66GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 5.25GB |
| 3 | `segmentio/kafka-go.makePartitions` | 5.0GB |
| 4 | `reflect.unsafe_NewArray` | 2.19GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.08GB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 2.06GB |
| 7 | `internal/evaluation.mergeMetadata` | 1.99GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.59GB |
| 9 | `database/sql.convertAssignRows` | 1.47GB |
| 10 | `reflect.MakeSlice` | 1.17GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.69GB | 250.11MB | 5.27GB | 0B |
| `evaluation.mergeMetadata` | 1.99GB | 105.03MB | 2.26GB | 0B |
| `local.(*Client).EvaluateV2` | 7.85GB | 415.59MB | 8.78GB | 0B |
| `local.topologicalSort` | 1.08GB | 62.00MB | 1.20GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.95GB | 465.64MB | 9.97GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 6.16MB | 0B | 18.87MB | 0B |
| `localEvaluation.getMapOfValue` | 8.95GB | 465.64MB | 9.97GB | 0B |
| `utils.ParseFeatureFlag` | 71.84MB | 39.20MB | 96.76MB | 0B |

**Total FF alloc (current snapshot):** 33.59GB  |  **24h avg:** 37.54GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 962/964 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/964 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/964 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.53MB | 958/964 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/964 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/964 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/964 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/964 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 960/964 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/964 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.9GB | 955/964 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 66.99GB | 305/964 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 66.26GB | 306/964 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 65.8GB | 300/964 | `██████████░░░░░ 68%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.96GB | 909/964 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.5GB | 954/964 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.68GB | 296/964 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 34.67GB | 291/964 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.36GB | 946/964 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.99GB | 907/964 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
