# Overview: prod
*Last updated: 2026-06-10 02:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T02:15 (2709 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,236 | avg: 13,939 | max: 84,644 | trend: INCREASING (+4.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▂▁▁▁▂▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂
```

**Heap InUse** (current: 435.6MB | avg: 222.8MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▂▂▁▂▁▂▁▁▁▁▁▁▁▂▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▄▂▁▂▂▁▁▃▃▁▂▂▁▄▃▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,236 | 26,639 | -7403 | 13,939 | 84,644 | INCREASING (+4.31/hr) |
| Heap InUse | 435.6MB | 564.2MB | -128.6MB | 222.8MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3300.4MB | 3297.1MB | +3.3MB | 2523.5MB | 6883.9MB | |
| Heap Objects | 1,426,673 | 1,343,783 | +82890 | 971,363 | 17,165,538 | |

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
| 2026-06-10 | 28 | 19,928 | 405.7MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `bytes.growSlice` | 38.22MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewWriterSize` | 17.08MB |
| 5 | `bufio.NewReaderSize` | 16.08MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.06MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 6.51MB |
| 10 | `compress/flate.NewWriter` | 5.29MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 116.21GB |
| 2 | `reflect.growslice` | 107.39GB |
| 3 | `jackskj/carta.getUniqueId` | 96.57GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 91.56GB |
| 5 | `reflect.unsafe_New` | 85.55GB |
| 6 | `fmt.Sprintf` | 79.15GB |
| 7 | `fmt.(*buffer).writeString` | 68.81GB |
| 8 | `carta/value.NewCell` | 61.04GB |
| 9 | `reflect.unsafe_NewArray` | 59.35GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 49.04GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.80GB | 5.80GB | 5.66GB | 0B |
| `evaluation.mergeMetadata` | 3.05GB | 3.05GB | 2.98GB | 0B |
| `local.(*Client).EvaluateV2` | 8.85GB | 8.84GB | 8.64GB | 0B |
| `local.topologicalSort` | 1.23GB | 1.23GB | 1.20GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.42GB | 8.41GB | 8.23GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.25GB | 1.24GB | 1.21GB | 0B |
| `localEvaluation.getMapOfValue` | 8.42GB | 8.41GB | 8.23GB | 0B |
| `utils.ParseFeatureFlag` | 8.43GB | 8.42GB | 8.24GB | 0B |

**Total FF alloc (current snapshot):** 45.45GB  |  **24h avg:** 44.40GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2709 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 59.71MB | 72/2709 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2360/2709 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2709 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.49MB | 2360/2709 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2709 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.68MB | 1799/2709 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2709 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2709 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2709 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2709 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2709 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2709 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2709 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2709 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 43.21GB | 1226/2709 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 34.26GB | 2083/2709 | `████░░░░░░░░░░░ 27%` |
| 8 | `reflect.growslice` | 32.7GB | 1921/2709 | `███░░░░░░░░░░░░ 26%` |
| 9 | `jackskj/carta.getUniqueId` | 28.33GB | 1937/2709 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2709 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
