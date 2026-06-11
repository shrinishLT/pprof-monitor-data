# Overview: prod
*Last updated: 2026-06-11 18:37 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T18:37 (3192 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,468 | avg: 14,267 | max: 84,644 | trend: INCREASING (+3.68/hr))
```
▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 490.0MB | avg: 234.4MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▇▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,468 | 18,075 | +1393 | 14,267 | 84,644 | INCREASING (+3.68/hr) |
| Heap InUse | 490.0MB | 363.4MB | +126.6MB | 234.4MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3327.4MB | 3340.4MB | -13.0MB | 2645.4MB | 6883.9MB | |
| Heap Objects | 2,265,180 | 832,621 | +1432559 | 1,009,421 | 17,165,538 | |

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
| 2026-06-11 | 224 | 16,141 | 304.3MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 36.48MB |
| 4 | `bufio.NewWriterSize` | 20.09MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 18.08MB |
| 6 | `bufio.NewReaderSize` | 16.07MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.04GB |
| 2 | `segmentio/kafka-go.makePartitions` | 171.89GB |
| 3 | `jackskj/carta.getUniqueId` | 161.38GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 142.56GB |
| 5 | `reflect.unsafe_New` | 142.22GB |
| 6 | `fmt.Sprintf` | 126.63GB |
| 7 | `fmt.(*buffer).writeString` | 111.97GB |
| 8 | `carta/value.NewCell` | 101.62GB |
| 9 | `reflect.unsafe_NewArray` | 87.7GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 81.47GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.37GB | 9.36GB | 9.12GB | 0B |
| `evaluation.mergeMetadata` | 4.90GB | 4.89GB | 4.77GB | 0B |
| `local.(*Client).EvaluateV2` | 14.28GB | 14.26GB | 13.90GB | 0B |
| `local.topologicalSort` | 1.98GB | 1.98GB | 1.93GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 13.63GB | 13.61GB | 13.28GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.97GB | 1.96GB | 1.89GB | 0B |
| `localEvaluation.getMapOfValue` | 13.63GB | 13.61GB | 13.28GB | 0B |
| `utils.ParseFeatureFlag` | 13.65GB | 13.63GB | 13.30GB | 0B |

**Total FF alloc (current snapshot):** 73.39GB  |  **24h avg:** 71.46GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3192 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.56MB | 87/3192 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2843/3192 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 31.4MB | 2843/3192 | `███████░░░░░░░░ 52%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3192 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3192 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.57MB | 2218/3192 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3192 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3192 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3192 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3192 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3192 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3192 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 64.2GB | 1709/3192 | `███████░░░░░░░░ 51%` |
| 5 | `reflect.growslice` | 55.11GB | 2404/3192 | `██████░░░░░░░░░ 44%` |
| 6 | `segmentio/kafka-go.makePartitions` | 54.94GB | 2566/3192 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3192 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 48.53GB | 2420/3192 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.unsafe_New` | 47.2GB | 2184/3192 | `█████░░░░░░░░░░ 37%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3192 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
