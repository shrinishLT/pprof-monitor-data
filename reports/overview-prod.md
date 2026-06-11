# Overview: prod
*Last updated: 2026-06-11 18:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T18:51 (3195 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,192 | avg: 14,270 | max: 84,644 | trend: INCREASING (+3.68/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▂▃▃▂▂
```

**Heap InUse** (current: 374.0MB | avg: 234.5MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
█▁▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▂▁▁▂▂▂▂▂▁▁▂▁▁▁▂▃▃▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,192 | 17,999 | -807 | 14,270 | 84,644 | INCREASING (+3.68/hr) |
| Heap InUse | 374.0MB | 409.4MB | -35.4MB | 234.5MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3331.0MB | 3329.6MB | +1.4MB | 2646.0MB | 6883.9MB | |
| Heap Objects | 1,549,656 | 1,646,508 | -96852 | 1,009,980 | 17,165,538 | |

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
| 2026-06-11 | 227 | 16,166 | 305.7MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 15.0MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 8.55MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `bufio.NewWriterSize` | 6.54MB |
| 9 | `crypto/tls.Client` | 4.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.06GB |
| 2 | `segmentio/kafka-go.makePartitions` | 172.23GB |
| 3 | `jackskj/carta.getUniqueId` | 161.43GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 142.56GB |
| 5 | `reflect.unsafe_New` | 142.25GB |
| 6 | `fmt.Sprintf` | 127.17GB |
| 7 | `fmt.(*buffer).writeString` | 111.98GB |
| 8 | `carta/value.NewCell` | 101.64GB |
| 9 | `reflect.unsafe_NewArray` | 87.86GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 81.49GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.40GB | 9.39GB | 9.15GB | 0B |
| `evaluation.mergeMetadata` | 4.92GB | 4.91GB | 4.78GB | 0B |
| `local.(*Client).EvaluateV2` | 14.33GB | 14.31GB | 13.94GB | 0B |
| `local.topologicalSort` | 1.98GB | 1.98GB | 1.93GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 13.67GB | 13.66GB | 13.32GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.97GB | 1.97GB | 1.90GB | 0B |
| `localEvaluation.getMapOfValue` | 13.67GB | 13.66GB | 13.32GB | 0B |
| `utils.ParseFeatureFlag` | 13.69GB | 13.68GB | 13.34GB | 0B |

**Total FF alloc (current snapshot):** 73.63GB  |  **24h avg:** 71.70GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3195 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.56MB | 87/3195 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2846/3195 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 31.42MB | 2846/3195 | `███████░░░░░░░░ 52%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3195 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3195 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.58MB | 2221/3195 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3195 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3195 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3195 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3195 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3195 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3195 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 64.34GB | 1712/3195 | `███████░░░░░░░░ 51%` |
| 5 | `reflect.growslice` | 55.26GB | 2407/3195 | `██████░░░░░░░░░ 44%` |
| 6 | `segmentio/kafka-go.makePartitions` | 55.07GB | 2569/3195 | `██████░░░░░░░░░ 44%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3195 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 48.67GB | 2423/3195 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.unsafe_New` | 47.33GB | 2187/3195 | `█████░░░░░░░░░░ 37%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3195 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
