# Overview: stage
*Last updated: 2026-06-04 13:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T13:00 (977 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,096 | avg: 14,224 | max: 28,205 | trend: stable (-0.38/hr))
```
▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄▁▁▁▁▁
```

**Heap InUse** (current: 115.0MB | avg: 166.1MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅▂▁▂▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,096 | 14,165 | -69 | 14,224 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 115.0MB | 128.3MB | -13.3MB | 166.1MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 121.8MB | 834.8MB | -713.0MB | 1284.8MB | 1805.8MB | |
| Heap Objects | 547,142 | 627,638 | -80496 | 883,621 | 2,707,946 | |

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
| 2026-06-04 | 26 | 14,156 | 139.4MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `aws/endpoints.init` | 3.0MB |
| 3 | `runtime.mallocgc` | 2.5MB |
| 4 | `internal/strs.(*Builder).grow` | 1.01MB |
| 5 | `sirupsen/logrus.NewEntry` | 1.0MB |
| 6 | `syscall.init.func1` | 525.43kB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 512.05kB |
| 8 | `regexp/syntax.(*parser).maybeConcat` | 512.03kB |
| 9 | `regexp.makeOnePass.func1` | 512.01kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `aws/endpoints.init` | 3.0MB |
| 3 | `runtime.mallocgc` | 2.5MB |
| 4 | `internal/strs.(*Builder).grow` | 1.01MB |
| 5 | `sirupsen/logrus.NewEntry` | 1.0MB |
| 6 | `syscall.init.func1` | 525.43kB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 512.05kB |
| 8 | `regexp/syntax.(*parser).maybeConcat` | 512.03kB |
| 9 | `kafka-go/protocol.structDecodeFuncOf.func1.1` | 512.02kB |
| 10 | `regexp.makeOnePass.func1` | 512.01kB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 0B | 8.28GB | 6.00GB | 0B |
| `evaluation.mergeMetadata` | 0B | 3.52GB | 2.56GB | 0B |
| `local.(*Client).EvaluateV2` | 0B | 13.90GB | 10.04GB | 0B |
| `local.topologicalSort` | 0B | 1.91GB | 1.38GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 0B | 15.81GB | 11.42GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 0B | 31.64MB | 18.18MB | 0B |
| `localEvaluation.getMapOfValue` | 0B | 15.81GB | 11.42GB | 0B |
| `utils.ParseFeatureFlag` | 0B | 203.07MB | 113.66MB | 0B |

**Total FF alloc (current snapshot):** 0B  |  **24h avg:** 42.94GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 975/977 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/977 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/977 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.48MB | 971/977 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/977 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/977 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/977 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/977 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 972/977 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/977 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.84GB | 967/977 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 64.58GB | 317/977 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 63.89GB | 318/977 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 63.39GB | 312/977 | `██████████░░░░░ 66%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.48GB | 921/977 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.04GB | 966/977 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/977 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/977 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.12GB | 957/977 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.78GB | 919/977 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.4x avg)
