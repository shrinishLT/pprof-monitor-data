# Overview: prod
*Last updated: 2026-06-08 14:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T14:55 (2285 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,701 | avg: 13,504 | max: 84,644 | trend: INCREASING (+4.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▅█▇▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 379.6MB | avg: 206.1MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▃▄▇█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,701 | 19,806 | -2105 | 13,504 | 84,644 | INCREASING (+4.41/hr) |
| Heap InUse | 379.6MB | 412.7MB | -33.1MB | 206.1MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 3205.0MB | 3206.4MB | -1.4MB | 2374.3MB | 6883.9MB | |
| Heap Objects | 614,679 | 1,415,338 | -800659 | 916,720 | 17,165,538 | |

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
| 2026-06-08 | 180 | 16,728 | 303.7MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 25.9MB |
| 4 | `bytes.growSlice` | 22.61MB |
| 5 | `fmt.Sprint` | 14.57MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 9 | `bufio.NewWriterSize` | 8.07MB |
| 10 | `bufio.NewReaderSize` | 5.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 67.94GB |
| 2 | `reflect.growslice` | 64.99GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.61GB |
| 4 | `jackskj/carta.getUniqueId` | 56.11GB |
| 5 | `reflect.unsafe_New` | 50.57GB |
| 6 | `fmt.(*buffer).writeString` | 40.58GB |
| 7 | `carta/value.NewCell` | 36.11GB |
| 8 | `reflect.unsafe_NewArray` | 34.63GB |
| 9 | `fmt.Sprintf` | 32.38GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 24.38GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.30GB | 2.28GB | 2.04GB | 0B |
| `evaluation.mergeMetadata` | 1.19GB | 1.18GB | 1.05GB | 0B |
| `local.(*Client).EvaluateV2` | 3.47GB | 3.45GB | 3.10GB | 0B |
| `local.topologicalSort` | 475.96MB | 472.40MB | 425.27MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.45GB | 3.43GB | 3.10GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 369.87MB | 367.81MB | 313.68MB | 0B |
| `localEvaluation.getMapOfValue` | 3.45GB | 3.43GB | 3.10GB | 0B |
| `utils.ParseFeatureFlag` | 3.45GB | 3.43GB | 3.10GB | 0B |

**Total FF alloc (current snapshot):** 18.13GB  |  **24h avg:** 16.21GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2285 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2285 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1936/2285 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2285 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 22.46MB | 1936/2285 | `████░░░░░░░░░░░ 26%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2285 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.46MB | 1414/2285 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.85MB | 45/2285 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2285 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2285 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2285 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2285 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2285 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2285 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2285 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2285 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2285 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 25.48GB | 802/2285 | `███░░░░░░░░░░░░ 20%` |
| 9 | `segmentio/kafka-go.makePartitions` | 19.48GB | 1659/2285 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `reflect.growslice` | 17.44GB | 1497/2285 | `██░░░░░░░░░░░░░ 13%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.3x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.8x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.6x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.9x avg)
