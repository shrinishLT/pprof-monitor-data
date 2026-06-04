# Overview: prod
*Last updated: 2026-06-04 19:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T19:10 (1185 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,058 | avg: 11,271 | max: 84,644 | trend: decreasing (-12.25/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▇▇▇▄▂▃▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁
```

**Heap InUse** (current: 211.0MB | avg: 171.0MB | max: 2823.8MB | trend: stable (-0.15MB/hr))
```
▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▃▃▅▅▅▄▅▃▃▃▂▃▃▄▄▂▂▂▂▃▃▃▂▂█▂▄▄▃▄▄▅▄▃▂▃▄▂▂▂▂▃▃▂▁▃▃▃▃▅▄▄▁▂▃▂▂▂▁▁▂▁▂▂▂▁▁▁▂▂▂▁▁▂▂▁▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,058 | 14,771 | +287 | 11,271 | 84,644 | decreasing (-12.25/hr) |
| Heap InUse | 211.0MB | 197.4MB | +13.6MB | 171.0MB | 2823.8MB | stable (-0.15MB/hr) |
| Heap Sys | 3860.2MB | 3860.7MB | -0.5MB | 2627.0MB | 6883.9MB | |
| Heap Objects | 1,236,412 | 953,620 | +282792 | 739,209 | 14,090,816 | |

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
| 2026-06-04 | 231 | 16,733 | 271.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.13MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `bufio.NewWriterSize` | 4.52MB |
| 7 | `reflect.unsafe_NewArray` | 3.02MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.33MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.84GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.84GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.5GB |
| 4 | `segmentio/kafka-go.makePartitions` | 2.89GB |
| 5 | `database/sql.convertAssignRows` | 2.23GB |
| 6 | `fmt.Sprintf` | 2.22GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.14GB |
| 8 | `reflect.unsafe_NewArray` | 1.5GB |
| 9 | `jackskj/carta.getUniqueId` | 1.48GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.14GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 277.24MB | 268.60MB | 322.84MB | 0B |
| `evaluation.mergeMetadata` | 145.53MB | 140.53MB | 168.11MB | 0B |
| `local.(*Client).EvaluateV2` | 431.47MB | 416.56MB | 499.81MB | 0B |
| `local.topologicalSort` | 61.75MB | 60.74MB | 71.95MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 381.05MB | 369.24MB | 460.77MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 89.87MB | 84.72MB | 83.97MB | 0B |
| `localEvaluation.getMapOfValue` | 381.05MB | 369.24MB | 460.77MB | 0B |
| `utils.ParseFeatureFlag` | 381.05MB | 369.24MB | 460.77MB | 0B |

**Total FF alloc (current snapshot):** 2.10GB  |  **24h avg:** 2.47GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1185 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1185 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 836/1185 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.63MB | 51/1185 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.68MB | 836/1185 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1185 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.3MB | 622/1185 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1185 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1185 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1185 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1185 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1185 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1185 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1185 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1185 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.17GB | 808/1185 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1185 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.69GB | 731/1185 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 11.65GB | 427/1185 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.55GB | 569/1185 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
