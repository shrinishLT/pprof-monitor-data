# Overview: stage
*Last updated: 2026-06-04 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:30 (972 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,482 | avg: 14,225 | max: 28,205 | trend: stable (-0.37/hr))
```
▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▁▁▁▅▁▁▁▆▁▁▁▄
```

**Heap InUse** (current: 203.7MB | avg: 166.3MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▂▂▂▂▄▃▄▃▁▅▄▂▃▂▃▄▄▃▄▄▅▃▄▂▂▅▃▄▄▃▃▄▂▂▃▃▁▃▃▄▁▂▂▂▁▂▁▄▂▄▂▄▄▁▄▂▂▁▁▄▃▂▂▄▃▂▂█▄▂▄▄▃▁▁▁▃▁▂▂▃▃▂▂▂▁▇▃▁▃▅▁▃▁▅
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,482 | 14,078 | +404 | 14,225 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 203.7MB | 99.6MB | +104.1MB | 166.3MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 834.6MB | 835.5MB | -0.9MB | 1287.8MB | 1805.8MB | |
| Heap Objects | 1,434,130 | 333,958 | +1100172 | 884,928 | 2,707,946 | |

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
| 2026-06-04 | 21 | 14,170 | 143.0MB | 258.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 7 | `bufio.NewWriterSize` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.23GB |
| 2 | `segmentio/kafka-go.makePartitions` | 12.1GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 6.98GB |
| 4 | `reflect.unsafe_NewArray` | 5.31GB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 3.38GB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 3.38GB |
| 7 | `internal/evaluation.mergeMetadata` | 3.25GB |
| 8 | `reflect.MakeSlice` | 2.9GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.14GB |
| 10 | `database/sql.convertAssignRows` | 1.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.65GB | 7.43GB | 5.87GB | 0B |
| `evaluation.mergeMetadata` | 3.25GB | 3.16GB | 2.51GB | 0B |
| `local.(*Client).EvaluateV2` | 12.83GB | 12.46GB | 9.82GB | 0B |
| `local.topologicalSort` | 1.77GB | 1.72GB | 1.35GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.61GB | 14.20GB | 11.17GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 21.75MB | 17.06MB | 17.18MB | 0B |
| `localEvaluation.getMapOfValue` | 14.61GB | 14.20GB | 11.17GB | 0B |
| `utils.ParseFeatureFlag` | 158.30MB | 141.52MB | 105.08MB | 0B |

**Total FF alloc (current snapshot):** 54.89GB  |  **24h avg:** 42.01GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 970/972 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.9MB | 37/972 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/972 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.51MB | 966/972 | `█████░░░░░░░░░░ 36%` |
| 5 | `database/sql.convertAssignRows` | 12.06MB | 39/972 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/972 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/972 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/972 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 968/972 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/972 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.17GB | 963/972 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.36GB | 313/972 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 64.65GB | 314/972 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 64.17GB | 308/972 | `██████████░░░░░ 67%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.63GB | 917/972 | `███████░░░░░░░░ 53%` |
| 6 | `reflect.unsafe_NewArray` | 41.18GB | 962/972 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 34.67GB | 291/972 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57GB | 297/972 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.21GB | 953/972 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 22.85GB | 915/972 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
