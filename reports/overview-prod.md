# Overview: prod
*Last updated: 2026-06-11 05:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T05:05 (3030 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,346 | avg: 14,141 | max: 84,644 | trend: INCREASING (+3.78/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 247.9MB | avg: 229.9MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂▂▂▂▃▂▂▂▂▂▂▁▁▁▁▃▃▃▂▁▁▁▂▂▁▁▂▁▂▂▃▂▅▃▂▂▂▂▂▁▁▂▃▁▂▁▂▂▂▂▃▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,346 | 14,575 | +771 | 14,141 | 84,644 | INCREASING (+3.78/hr) |
| Heap InUse | 247.9MB | 268.2MB | -20.3MB | 229.9MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3344.5MB | 3344.4MB | +0.1MB | 2608.9MB | 6883.9MB | |
| Heap Objects | 641,416 | 770,794 | -129378 | 992,642 | 17,165,538 | |

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
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 62 | 14,890 | 268.8MB | 428.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 9.05MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewReaderSize` | 4.04MB |
| 7 | `fmt.Sprint` | 3.52MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `fmt.Sprintf` | 3.01MB |
| 10 | `bufio.NewWriterSize` | 2.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 153.2GB |
| 2 | `reflect.growslice` | 147.73GB |
| 3 | `jackskj/carta.getUniqueId` | 134.14GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 119.64GB |
| 5 | `reflect.unsafe_New` | 118.26GB |
| 6 | `fmt.Sprintf` | 109.6GB |
| 7 | `fmt.(*buffer).writeString` | 93.3GB |
| 8 | `carta/value.NewCell` | 84.41GB |
| 9 | `reflect.unsafe_NewArray` | 78.29GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 69.09GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.07GB | 8.07GB | 7.93GB | 0B |
| `evaluation.mergeMetadata` | 4.23GB | 4.22GB | 4.15GB | 0B |
| `local.(*Client).EvaluateV2` | 12.31GB | 12.30GB | 12.09GB | 0B |
| `local.topologicalSort` | 1.70GB | 1.70GB | 1.67GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.74GB | 11.73GB | 11.51GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.69GB | 1.69GB | 1.68GB | 0B |
| `localEvaluation.getMapOfValue` | 11.74GB | 11.73GB | 11.51GB | 0B |
| `utils.ParseFeatureFlag` | 11.75GB | 11.74GB | 11.53GB | 0B |

**Total FF alloc (current snapshot):** 63.23GB  |  **24h avg:** 62.06GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.39MB | 56/3030 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.2MB | 84/3030 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2681/3030 | `████████░░░░░░░ 58%` |
| 4 | `runtime.mallocgc` | 30.24MB | 2681/3030 | `███████░░░░░░░░ 48%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3030 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3030 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.37MB | 2079/3030 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.4MB | 61/3030 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3030 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3030 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3030 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3030 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3030 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 56.61GB | 1547/3030 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3030 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 47.68GB | 2404/3030 | `█████░░░░░░░░░░ 38%` |
| 7 | `reflect.growslice` | 46.87GB | 2242/3030 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3030 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 41.04GB | 2258/3030 | `████░░░░░░░░░░░ 32%` |
| 10 | `reflect.unsafe_New` | 40.18GB | 2022/3030 | `████░░░░░░░░░░░ 32%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
