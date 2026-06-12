# Overview: prod
*Last updated: 2026-06-12 08:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T08:31 (3359 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,933 | avg: 14,343 | max: 84,644 | trend: INCREASING (+3.41/hr))
```
▁▂▁▁▅▃▁▂▁▁▁▂▂▁▁▁▂▂▂▂▁▁▁▁▂▂▂▁▁▁▁▁▁▅▂▁▂▂▂▂▂▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▃█▁
```

**Heap InUse** (current: 279.5MB | avg: 237.4MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▂▁▂▄▄▃▂▂▃▂▃▃▁▃▁▁▂▂▃▁▃▁▁▁▃▃▁▃▂▁▂▂▄▂▃▂▂▂▄▂▁▄▂▁▃▃▂▁▂▂▃▂▃▂▂▂▂▁▂▁▁▃▃▂▂▁▂▃▃▄▄▂▂▃▁▂▃▂▁▃▂▁▃▁▂▄▂▁▁▁▃▁▄█▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,933 | 20,200 | -5267 | 14,343 | 84,644 | INCREASING (+3.41/hr) |
| Heap InUse | 279.5MB | 490.2MB | -210.7MB | 237.4MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3328.1MB | 3321.7MB | +6.4MB | 2679.4MB | 6883.9MB | |
| Heap Objects | 945,526 | 2,063,035 | -1117509 | 1,018,794 | 17,165,538 | |

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
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 103 | 14,890 | 262.1MB | 490.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 14.12MB |
| 4 | `bufio.NewWriterSize` | 9.56MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 8 | `bufio.NewReaderSize` | 5.05MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 193.59GB |
| 2 | `segmentio/kafka-go.makePartitions` | 191.01GB |
| 3 | `jackskj/carta.getUniqueId` | 174.66GB |
| 4 | `reflect.unsafe_New` | 154.24GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 151.82GB |
| 6 | `fmt.Sprintf` | 140.76GB |
| 7 | `fmt.(*buffer).writeString` | 121.12GB |
| 8 | `carta/value.NewCell` | 110.25GB |
| 9 | `reflect.unsafe_NewArray` | 97.42GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 86.58GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.49GB | 10.48GB | 10.38GB | 0B |
| `evaluation.mergeMetadata` | 5.47GB | 5.47GB | 5.41GB | 0B |
| `local.(*Client).EvaluateV2` | 15.97GB | 15.97GB | 15.81GB | 0B |
| `local.topologicalSort` | 2.22GB | 2.22GB | 2.20GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.26GB | 15.25GB | 15.09GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.18GB | 2.18GB | 2.17GB | 0B |
| `localEvaluation.getMapOfValue` | 15.26GB | 15.25GB | 15.09GB | 0B |
| `utils.ParseFeatureFlag` | 15.28GB | 15.28GB | 15.11GB | 0B |

**Total FF alloc (current snapshot):** 82.12GB  |  **24h avg:** 81.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.55MB | 64/3359 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.55MB | 91/3359 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3010/3359 | `█████████░░░░░░ 65%` |
| 4 | `runtime.mallocgc` | 32.45MB | 3010/3359 | `████████░░░░░░░ 58%` |
| 5 | `database/sql.convertAssignRows` | 25.78MB | 113/3359 | `██████░░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3359 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.43MB | 2365/3359 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3359 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.81MB | 75/3359 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3359 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3359 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3359 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3359 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.42GB | 1876/3359 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 63.38GB | 2571/3359 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.67GB | 2733/3359 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.09GB | 2587/3359 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 54.22GB | 2351/3359 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3359 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.2GB | 2098/3359 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
