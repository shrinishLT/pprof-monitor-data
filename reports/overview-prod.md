# Overview: prod
*Last updated: 2026-06-05 02:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T02:05 (1268 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,037 | avg: 11,550 | max: 84,644 | trend: decreasing (-7.55/hr))
```
▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁
```

**Heap InUse** (current: 182.6MB | avg: 177.0MB | max: 3154.1MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,037 | 15,394 | -357 | 11,550 | 84,644 | decreasing (-7.55/hr) |
| Heap InUse | 182.6MB | 183.7MB | -1.1MB | 177.0MB | 3154.1MB | stable (-0.07MB/hr) |
| Heap Sys | 4656.0MB | 4655.6MB | +0.4MB | 2671.1MB | 6883.9MB | |
| Heap Objects | 791,211 | 635,803 | +155408 | 774,691 | 17,165,538 | |

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
| 2026-06-05 | 26 | 14,881 | 306.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.54MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `bufio.NewReaderSize` | 3.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `bufio.NewWriterSize` | 2.51MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 16.51GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.57GB |
| 3 | `segmentio/kafka-go.makePartitions` | 4.12GB |
| 4 | `fmt.Sprintf` | 2.82GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.65GB |
| 6 | `reflect.growslice` | 2.62GB |
| 7 | `jackskj/carta.getUniqueId` | 2.61GB |
| 8 | `reflect.unsafe_New` | 2.27GB |
| 9 | `reflect.unsafe_NewArray` | 2.14GB |
| 10 | `database/sql.convertAssignRows` | 2.14GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 249.73MB | 247.21MB | 226.39MB | 0B |
| `evaluation.mergeMetadata` | 126.03MB | 125.03MB | 116.96MB | 0B |
| `local.(*Client).EvaluateV2` | 364.94MB | 360.36MB | 337.15MB | 0B |
| `local.topologicalSort` | 54.64MB | 53.64MB | 47.42MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 344.60MB | 339.51MB | 302.56MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 48.53MB | 48.53MB | 61.80MB | 0B |
| `localEvaluation.getMapOfValue` | 344.60MB | 339.51MB | 302.56MB | 0B |
| `utils.ParseFeatureFlag` | 344.60MB | 339.51MB | 302.65MB | 0B |

**Total FF alloc (current snapshot):** 1.83GB  |  **24h avg:** 1.66GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.25MB | 26/1268 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.68MB | 42/1268 | `██████████████░ 95%` |
| 3 | `database/sql.convertAssignRows` | 37.1MB | 54/1268 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 919/1268 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 18.9MB | 919/1268 | `███░░░░░░░░░░░░ 23%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1268 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 14.9MB | 696/1268 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1268 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1268 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1268 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1268 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1268 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1268 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1268 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1268 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 36.45GB | 891/1268 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1268 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.3GB | 814/1268 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 10.39GB | 506/1268 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1268 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
