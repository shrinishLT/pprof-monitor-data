# Overview: prod
*Last updated: 2026-06-11 10:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T10:11 (3091 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 24,472 | avg: 14,160 | max: 84,644 | trend: INCREASING (+3.63/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▃▄█
```

**Heap InUse** (current: 590.9MB | avg: 230.8MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▂▂▁▁▂▁▂▂▃▂▅▃▂▂▂▂▂▁▁▂▃▁▂▁▂▂▂▂▃▁▂▂▂▃▂▄▂▃▂▁▁▂▂▁▁▃▃▂▃▂▂▂▁▁▂▁▁▂▂▁▂▁▁▁▂▂▃▁▂▂▂▂▁▂▁▁▁▂▁▂▁▂▂▂▂▂▃▂▂▃▄▅█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 28%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 24,472 | 19,883 | +4589 | 14,160 | 84,644 | INCREASING (+3.63/hr) |
| Heap InUse | 590.9MB | 450.1MB | +140.8MB | 230.8MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3315.5MB | 3333.7MB | -18.2MB | 2623.4MB | 6883.9MB | |
| Heap Objects | 3,237,350 | 2,409,708 | +827642 | 997,757 | 17,165,538 | |

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
| 2026-06-11 | 123 | 14,983 | 271.9MB | 590.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 52.27MB |
| 2 | `runtime.mallocgc` | 50.47MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewReaderSize` | 27.62MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 26.62MB |
| 6 | `bufio.NewWriterSize` | 26.14MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 12.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 10 | `reflect.growslice` | 6.84MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 164.69GB |
| 2 | `segmentio/kafka-go.makePartitions` | 160.27GB |
| 3 | `jackskj/carta.getUniqueId` | 148.69GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 131.55GB |
| 5 | `reflect.unsafe_New` | 131.07GB |
| 6 | `fmt.Sprintf` | 117.11GB |
| 7 | `fmt.(*buffer).writeString` | 103.94GB |
| 8 | `carta/value.NewCell` | 93.63GB |
| 9 | `reflect.unsafe_NewArray` | 81.83GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 76.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.40GB | 8.39GB | 8.26GB | 0B |
| `evaluation.mergeMetadata` | 4.39GB | 4.38GB | 4.32GB | 0B |
| `local.(*Client).EvaluateV2` | 12.79GB | 12.78GB | 12.58GB | 0B |
| `local.topologicalSort` | 1.77GB | 1.76GB | 1.74GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.23GB | 12.21GB | 12.01GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.73GB | 1.73GB | 1.72GB | 0B |
| `localEvaluation.getMapOfValue` | 12.23GB | 12.21GB | 12.01GB | 0B |
| `utils.ParseFeatureFlag` | 12.25GB | 12.23GB | 12.03GB | 0B |

**Total FF alloc (current snapshot):** 65.79GB  |  **24h avg:** 64.67GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3091 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3091 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2742/3091 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.69MB | 2742/3091 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3091 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3091 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.25MB | 2123/3091 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).dialConn` | 14.23MB | 62/3091 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3091 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3091 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3091 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3091 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3091 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.34GB | 1608/3091 | `███████░░░░░░░░ 47%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3091 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 50.38GB | 2465/3091 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 49.84GB | 2303/3091 | `█████░░░░░░░░░░ 39%` |
| 8 | `jackskj/carta.getUniqueId` | 43.73GB | 2319/3091 | `█████░░░░░░░░░░ 34%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3091 | `█████░░░░░░░░░░ 34%` |
| 10 | `reflect.unsafe_New` | 42.71GB | 2083/3091 | `█████░░░░░░░░░░ 34%` |

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
