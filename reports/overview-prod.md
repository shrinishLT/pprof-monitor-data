# Overview: prod
*Last updated: 2026-06-06 07:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T07:55 (1625 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,720 | avg: 12,537 | max: 84,644 | trend: INCREASING (+2.05/hr))
```
▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇▅▂▁▂▃▁▂▂▆▃▁▁▁▁▁▁▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 155.4MB | avg: 189.5MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▃▅▃▄▁▁▄▂▂▅▅▂▆▇▅▁▁▂▅█▇▃▁▃▄▂▃▂▆▅▃▁▂▃▁▂▅▄▂▂▂▁▂▂▂▂▁▁▁▂▁▁▁▁▁▃▃▁▁▁▁▂▃▁▄▄▁▂▁▁▁▁▂▂▂▂▂▂▂▁▁▂▂▁▁▁▁▂▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,720 | 15,257 | -537 | 12,537 | 84,644 | INCREASING (+2.05/hr) |
| Heap InUse | 155.4MB | 233.7MB | -78.3MB | 189.5MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1045.9MB | 1041.5MB | +4.4MB | 2455.3MB | 6883.9MB | |
| Heap Objects | 336,479 | 1,147,755 | -811276 | 837,472 | 17,165,538 | |

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
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 96 | 15,956 | 238.6MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 4.53MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `reflect.mapassign_faststr0` | 3.5MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `reflect.unsafe_NewArray` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 29.99GB |
| 2 | `segmentio/kafka-go.makePartitions` | 28.03GB |
| 3 | `reflect.growslice` | 27.96GB |
| 4 | `jackskj/carta.getUniqueId` | 26.06GB |
| 5 | `reflect.unsafe_New` | 22.45GB |
| 6 | `fmt.(*buffer).writeString` | 19.09GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.06GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 18.48GB |
| 9 | `carta/value.NewCell` | 15.94GB |
| 10 | `strconv.appendQuotedWith` | 14.52GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.52GB | 1.52GB | 1.43GB | 0B |
| `evaluation.mergeMetadata` | 807.20MB | 806.20MB | 757.44MB | 0B |
| `local.(*Client).EvaluateV2` | 2.33GB | 2.32GB | 2.19GB | 0B |
| `local.topologicalSort` | 337.09MB | 336.58MB | 319.23MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.24GB | 2.23GB | 2.10GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 316.29MB | 316.29MB | 307.66MB | 0B |
| `localEvaluation.getMapOfValue` | 2.24GB | 2.23GB | 2.10GB | 0B |
| `utils.ParseFeatureFlag` | 2.24GB | 2.24GB | 2.10GB | 0B |

**Total FF alloc (current snapshot):** 11.98GB  |  **24h avg:** 11.27GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1625 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1625 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1625 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1276/1625 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1625 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.04MB | 1276/1625 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.78MB | 1001/1625 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1625 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1625 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1625 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1625 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1625 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1625 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1625 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1625 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1625 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1625 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1625 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.3GB | 809/1625 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.9GB | 336/1625 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
