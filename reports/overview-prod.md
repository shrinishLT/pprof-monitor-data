# Overview: prod
*Last updated: 2026-06-11 07:52 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T07:52 (3063 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,898 | avg: 14,149 | max: 84,644 | trend: INCREASING (+3.69/hr))
```
▁▂▂▁▁▁▁▁▁▁▂▂▁▁▂▃▁▂▂▂▃▂▂▁▂▂▂▂▁▁▁▁▁▂▁▁▁▁▁▂▃█▂▁▁▂▂▁▁▁▄▂▁▁▂▁▂▃▂▂▁▁▂▁▂▃▄▃▂▂▁▁▁▁▁▂▄▂▃▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▃
```

**Heap InUse** (current: 299.7MB | avg: 230.3MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▃▃▄▃▂▃▂▁▄▃▃▄▂▄▄▃▂▃▃▃▂▂▂▂▄▄▄▃▂▂▁▃▃▂▁▃▁▃▃▄▃█▄▃▃▂▃▃▂▂▃▄▂▄▂▃▃▃▄▅▂▃▂▃▄▄▇▃▅▄▁▂▃▂▂▂▄▄▃▅▄▃▂▁▁▃▂▁▃▃▁▃▂▁▁▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,898 | 14,235 | +1663 | 14,149 | 84,644 | INCREASING (+3.69/hr) |
| Heap InUse | 299.7MB | 204.7MB | +95.0MB | 230.3MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3341.2MB | 3344.8MB | -3.6MB | 2616.8MB | 6883.9MB | |
| Heap Objects | 1,123,877 | 727,125 | +396752 | 994,279 | 17,165,538 | |

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
| 2026-06-11 | 95 | 14,876 | 267.7MB | 428.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 7.04MB |
| 6 | `bufio.NewReaderSize` | 5.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `bufio.NewWriterSize` | 3.56MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 159.18GB |
| 2 | `segmentio/kafka-go.makePartitions` | 157.07GB |
| 3 | `jackskj/carta.getUniqueId` | 143.44GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 128.72GB |
| 5 | `reflect.unsafe_New` | 126.62GB |
| 6 | `fmt.Sprintf` | 114.77GB |
| 7 | `fmt.(*buffer).writeString` | 100.76GB |
| 8 | `carta/value.NewCell` | 90.36GB |
| 9 | `reflect.unsafe_NewArray` | 80.24GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 74.63GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.24GB | 8.23GB | 8.12GB | 0B |
| `evaluation.mergeMetadata` | 4.30GB | 4.30GB | 4.24GB | 0B |
| `local.(*Client).EvaluateV2` | 12.54GB | 12.52GB | 12.37GB | 0B |
| `local.topologicalSort` | 1.73GB | 1.73GB | 1.71GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.97GB | 11.96GB | 11.80GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.71GB | 1.71GB | 1.70GB | 0B |
| `localEvaluation.getMapOfValue` | 11.97GB | 11.96GB | 11.80GB | 0B |
| `utils.ParseFeatureFlag` | 11.99GB | 11.97GB | 11.81GB | 0B |

**Total FF alloc (current snapshot):** 64.46GB  |  **24h avg:** 63.54GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3063 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3063 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2714/3063 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.49MB | 2714/3063 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3063 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3063 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.29MB | 2103/3063 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).dialConn` | 14.4MB | 61/3063 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3063 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3063 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3063 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3063 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3063 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 58.1GB | 1580/3063 | `██████░░░░░░░░░ 46%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3063 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 49.14GB | 2437/3063 | `█████░░░░░░░░░░ 39%` |
| 7 | `reflect.growslice` | 48.47GB | 2275/3063 | `█████░░░░░░░░░░ 38%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3063 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 42.5GB | 2291/3063 | `█████░░░░░░░░░░ 33%` |
| 10 | `reflect.unsafe_New` | 41.55GB | 2055/3063 | `████░░░░░░░░░░░ 33%` |

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
