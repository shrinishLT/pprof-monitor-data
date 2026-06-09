# Overview: prod
*Last updated: 2026-06-09 18:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T18:55 (2621 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,865 | avg: 13,829 | max: 84,644 | trend: INCREASING (+4.23/hr))
```
▁▂▂▃▂▂▂▁▁▁▁▁▁▁▂▅▂▃▄▄▃▂▂▁▁▃▁▂▁▃▂▁▁▁▁▄▅▄▅▆▃▃▁▂▄▅▄▅▄▂▁▁▅▃▆█▄▃▃▃▂▃▁▂▄▂▁▁▃▃▄▁▁▂▂▂▂▁▁▁▁▁▂▁▁▂▁▃▂▂▂▁▂▄▅▅
```

**Heap InUse** (current: 344.5MB | avg: 218.9MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▂▂▂▁▄▃▁▂▁▃▃▂▃▅▂▂▃▂▃▂▃▂▁▃▂▁▃▃▄▂▃▇▄▃▆▄▄▄▃▂▁▃▅▃▃▆▃▂▂▃▅▂▃█▅▂▂▂▃▂▂▂▄▃▁▃▂▃▂▂▁▃▃▃▃▃▂▁▂▂▂▂▃▂▂▃▂▃▃▃▂▃▄▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,865 | 16,170 | -305 | 13,829 | 84,644 | INCREASING (+4.23/hr) |
| Heap InUse | 344.5MB | 338.0MB | +6.5MB | 218.9MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3345.7MB | 3345.2MB | +0.5MB | 2496.5MB | 6883.9MB | |
| Heap Objects | 1,406,402 | 1,316,623 | +89779 | 957,870 | 17,165,538 | |

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
| 2026-06-09 | 228 | 16,221 | 303.9MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 18.91MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 6.05MB |
| 7 | `bufio.NewReaderSize` | 4.53MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 106.21GB |
| 2 | `reflect.growslice` | 104.57GB |
| 3 | `jackskj/carta.getUniqueId` | 93.28GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.16GB |
| 5 | `reflect.unsafe_New` | 82.69GB |
| 6 | `fmt.Sprintf` | 69.96GB |
| 7 | `fmt.(*buffer).writeString` | 67.16GB |
| 8 | `carta/value.NewCell` | 59.01GB |
| 9 | `reflect.unsafe_NewArray` | 54.3GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 46.65GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.10GB | 5.09GB | 4.86GB | 0B |
| `evaluation.mergeMetadata` | 2.68GB | 2.67GB | 2.55GB | 0B |
| `local.(*Client).EvaluateV2` | 7.79GB | 7.77GB | 7.42GB | 0B |
| `local.topologicalSort` | 1.08GB | 1.08GB | 1.04GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.42GB | 7.41GB | 7.12GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.07GB | 1.07GB | 1011.18MB | 0B |
| `localEvaluation.getMapOfValue` | 7.42GB | 7.41GB | 7.12GB | 0B |
| `utils.ParseFeatureFlag` | 7.44GB | 7.42GB | 7.13GB | 0B |

**Total FF alloc (current snapshot):** 40.00GB  |  **24h avg:** 38.22GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.78MB | 42/2621 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 62.08MB | 69/2621 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2272/2621 | `██████░░░░░░░░░ 45%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2621 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 26.6MB | 2272/2621 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2621 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.34MB | 1720/2621 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.92MB | 51/2621 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2621 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2621 | `█░░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2621 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2621 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2621 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2621 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2621 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 39.56GB | 1138/2621 | `████░░░░░░░░░░░ 31%` |
| 7 | `segmentio/kafka-go.makePartitions` | 30.87GB | 1995/2621 | `███░░░░░░░░░░░░ 24%` |
| 8 | `reflect.growslice` | 29.23GB | 1833/2621 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2621 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2621 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.4x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.6x avg)
