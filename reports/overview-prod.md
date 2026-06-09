# Overview: prod
*Last updated: 2026-06-10 03:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T03:45 (2727 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,067 | avg: 13,947 | max: 84,644 | trend: INCREASING (+4.25/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▂▁▁▁▂▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 337.1MB | avg: 223.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▂▂▂▂▂▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▄▂▁▃▂▁▁▃▃▁▂▂▁▄▃▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,067 | 14,844 | +223 | 13,947 | 84,644 | INCREASING (+4.25/hr) |
| Heap InUse | 337.1MB | 245.0MB | +92.1MB | 223.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3311.5MB | 3312.1MB | -0.6MB | 2528.7MB | 6883.9MB | |
| Heap Objects | 1,768,675 | 918,328 | +850347 | 972,983 | 17,165,538 | |

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
| 2026-06-10 | 46 | 18,043 | 353.6MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `compress/flate.NewWriter` | 5.29MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 8 | `bufio.NewReaderSize` | 3.53MB |
| 9 | `bufio.NewWriterSize` | 3.53MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 118.27GB |
| 2 | `reflect.growslice` | 108.19GB |
| 3 | `jackskj/carta.getUniqueId` | 97.26GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 91.64GB |
| 5 | `reflect.unsafe_New` | 86.16GB |
| 6 | `fmt.Sprintf` | 80.03GB |
| 7 | `fmt.(*buffer).writeString` | 69.27GB |
| 8 | `carta/value.NewCell` | 61.5GB |
| 9 | `reflect.unsafe_NewArray` | 60.37GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 49.22GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.88GB | 5.87GB | 5.76GB | 0B |
| `evaluation.mergeMetadata` | 3.10GB | 3.09GB | 3.03GB | 0B |
| `local.(*Client).EvaluateV2` | 8.97GB | 8.96GB | 8.79GB | 0B |
| `local.topologicalSort` | 1.25GB | 1.25GB | 1.23GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.54GB | 8.53GB | 8.37GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.25GB | 1.25GB | 1.23GB | 0B |
| `localEvaluation.getMapOfValue` | 8.54GB | 8.53GB | 8.37GB | 0B |
| `utils.ParseFeatureFlag` | 8.56GB | 8.55GB | 8.39GB | 0B |

**Total FF alloc (current snapshot):** 46.10GB  |  **24h avg:** 45.18GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 77.45MB | 44/2727 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 58.19MB | 74/2727 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2378/2727 | `███████░░░░░░░░ 47%` |
| 4 | `database/sql.convertAssignRows` | 29.71MB | 95/2727 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 27.67MB | 2378/2727 | `█████░░░░░░░░░░ 35%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2727 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 15.64MB | 1813/2727 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2727 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2727 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2727 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2727 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2727 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2727 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2727 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 43.91GB | 1244/2727 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2727 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 34.98GB | 2101/2727 | `████░░░░░░░░░░░ 27%` |
| 8 | `reflect.growslice` | 33.4GB | 1939/2727 | `████░░░░░░░░░░░ 26%` |
| 9 | `jackskj/carta.getUniqueId` | 28.96GB | 1955/2727 | `███░░░░░░░░░░░░ 23%` |
| 10 | `reflect.unsafe_New` | 28.69GB | 1719/2727 | `███░░░░░░░░░░░░ 22%` |

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
