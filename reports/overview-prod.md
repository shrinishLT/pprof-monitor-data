# Overview: prod
*Last updated: 2026-06-05 10:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:05 (1364 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,565 | avg: 11,789 | max: 84,644 | trend: decreasing (-4.11/hr))
```
▁▁▁▃▁▁▁▂▁▁▁▂▁▁▁▁▁▂▃▂▃▄▄▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▂▂▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▂▂▂▄█
```

**Heap InUse** (current: 358.6MB | avg: 180.1MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,565 | 16,992 | +3573 | 11,789 | 84,644 | decreasing (-4.11/hr) |
| Heap InUse | 358.6MB | 241.3MB | +117.3MB | 180.1MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 4408.0MB | 4420.8MB | -12.8MB | 2696.8MB | 6883.9MB | |
| Heap Objects | 1,777,809 | 1,267,285 | +510524 | 803,413 | 17,165,538 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 122 | 14,932 | 239.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.15MB |
| 3 | `bufio.NewReaderSize` | 15.56MB |
| 4 | `runtime.mallocgc` | 14.01MB |
| 5 | `bufio.NewWriterSize` | 12.05MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 6.01MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 10 | `crypto/tls.Client` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 2 | `reflect.growslice` | 5.07GB |
| 3 | `jackskj/carta.getUniqueId` | 5.03GB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.25GB |
| 5 | `reflect.unsafe_New` | 4.21GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 3.26GB |
| 7 | `carta/value.NewCell` | 3.01GB |
| 8 | `fmt.(*buffer).writeString` | 2.97GB |
| 9 | `fmt.Sprintf` | 2.81GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 2.66GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 230.78MB | 223.68MB | 152.03MB | 0B |
| `evaluation.mergeMetadata` | 115.03MB | 111.53MB | 77.06MB | 0B |
| `local.(*Client).EvaluateV2` | 347.14MB | 335.89MB | 227.93MB | 0B |
| `local.topologicalSort` | 46.53MB | 45.53MB | 32.62MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 366.53MB | 352.72MB | 232.25MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 18.01MB | 18.01MB | 19.32MB | 0B |
| `localEvaluation.getMapOfValue` | 366.53MB | 352.72MB | 232.25MB | 0B |
| `utils.ParseFeatureFlag` | 366.53MB | 352.72MB | 232.44MB | 0B |

**Total FF alloc (current snapshot):** 1.81GB  |  **24h avg:** 1.18GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1364 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1364 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1364 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1015/1364 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1364 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.98MB | 1015/1364 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.08MB | 778/1364 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1364 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1364 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.71MB | 17/1364 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1364 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1364 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1364 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1364 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1364 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.14GB | 986/1364 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1364 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.11GB | 909/1364 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.5GB | 189/1364 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.46GB | 564/1364 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
