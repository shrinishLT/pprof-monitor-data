# Overview: prod
*Last updated: 2026-06-09 00:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T00:35 (2401 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,899 | avg: 13,604 | max: 84,644 | trend: INCREASING (+4.27/hr))
```
▅▄▅█▃▁▁▄▃▃▃▂▂▁▁▁▂▆▃▂▂▂▁▂▁▁▁▁▁▁▁▃▂▁▂▂▆▃▄▂▂▆▃▂▄▂▂▃▁▁▂▁▂▃▂▁▁▁▁▂▁▁▂▅▂▁▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▂▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 302.9MB | avg: 210.9MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▅▄▄▅█▁▂▃▃▃▄▂▂▂▂▁▂▆▃▃▂▃▃▂▂▃▂▂▁▁▃▃▃▂▃▂▅▃▄▂▂▅▄▂▅▃▂▃▃▃▂▁▂▃▂▁▂▂▁▂▁▂▂▄▄▁▁▂▂▂▁▃▂▂▂▂▁▃▂▁▁▁▂▃▂▃▁▂▂▂▂▁▁▁▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,899 | 14,470 | +429 | 13,604 | 84,644 | INCREASING (+4.27/hr) |
| Heap InUse | 302.9MB | 230.7MB | +72.2MB | 210.9MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3342.5MB | 3342.5MB | +0.0MB | 2420.3MB | 6883.9MB | |
| Heap Objects | 1,911,470 | 850,378 | +1061092 | 933,817 | 17,165,538 | |

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
| 2026-06-09 | 8 | 14,446 | 252.3MB | 302.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.54MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `bufio.NewWriterSize` | 3.01MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 2.67MB |
| 10 | `bufio.NewReaderSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 81.09GB |
| 2 | `reflect.growslice` | 66.24GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.2GB |
| 4 | `jackskj/carta.getUniqueId` | 57.72GB |
| 5 | `reflect.unsafe_New` | 51.84GB |
| 6 | `fmt.Sprintf` | 42.61GB |
| 7 | `reflect.unsafe_NewArray` | 41.47GB |
| 8 | `fmt.(*buffer).writeString` | 41.16GB |
| 9 | `carta/value.NewCell` | 37.08GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 26.11GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.49GB | 3.48GB | 3.34GB | 0B |
| `evaluation.mergeMetadata` | 1.81GB | 1.81GB | 1.74GB | 0B |
| `local.(*Client).EvaluateV2` | 5.31GB | 5.30GB | 5.08GB | 0B |
| `local.topologicalSort` | 748.37MB | 748.37MB | 719.74MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.07GB | 5.06GB | 4.85GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 739.84MB | 738.34MB | 714.83MB | 0B |
| `localEvaluation.getMapOfValue` | 5.07GB | 5.06GB | 4.85GB | 0B |
| `utils.ParseFeatureFlag` | 5.08GB | 5.07GB | 4.86GB | 0B |

**Total FF alloc (current snapshot):** 27.29GB  |  **24h avg:** 26.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2401 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2401 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2052/2401 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 89/2401 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 24.04MB | 2052/2401 | `████░░░░░░░░░░░ 28%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2401 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.2MB | 1523/2401 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2401 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2401 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2401 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2401 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2401 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2401 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2401 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2401 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 29.85GB | 918/2401 | `███░░░░░░░░░░░░ 23%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2401 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2401 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 23.08GB | 1775/2401 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `reflect.growslice` | 20.91GB | 1613/2401 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
