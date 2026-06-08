# Overview: prod
*Last updated: 2026-06-08 16:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T16:45 (2307 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,639 | avg: 13,534 | max: 84,644 | trend: INCREASING (+4.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▅█▇▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 361.7MB | avg: 207.6MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▃▄▇█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,639 | 18,191 | -552 | 13,534 | 84,644 | INCREASING (+4.44/hr) |
| Heap InUse | 361.7MB | 440.1MB | -78.4MB | 207.6MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 3334.7MB | 3331.5MB | +3.2MB | 2382.9MB | 6883.9MB | |
| Heap Objects | 1,049,939 | 2,113,440 | -1063501 | 920,596 | 17,165,538 | |

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
| 2026-06-08 | 202 | 16,723 | 310.1MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 24.12MB |
| 4 | `bufio.NewReaderSize` | 11.04MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `bufio.NewWriterSize` | 7.57MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 4.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 70.43GB |
| 2 | `reflect.growslice` | 65.43GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.76GB |
| 4 | `jackskj/carta.getUniqueId` | 56.7GB |
| 5 | `reflect.unsafe_New` | 51.01GB |
| 6 | `fmt.(*buffer).writeString` | 40.88GB |
| 7 | `carta/value.NewCell` | 36.43GB |
| 8 | `reflect.unsafe_NewArray` | 35.97GB |
| 9 | `fmt.Sprintf` | 35.85GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 24.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.59GB | 2.59GB | 2.29GB | 0B |
| `evaluation.mergeMetadata` | 1.35GB | 1.35GB | 1.18GB | 0B |
| `local.(*Client).EvaluateV2` | 3.92GB | 3.91GB | 3.46GB | 0B |
| `local.topologicalSort` | 549.31MB | 548.29MB | 477.48MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.83GB | 3.82GB | 3.43GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 481.20MB | 476.12MB | 378.14MB | 0B |
| `localEvaluation.getMapOfValue` | 3.83GB | 3.82GB | 3.43GB | 0B |
| `utils.ParseFeatureFlag` | 3.83GB | 3.83GB | 3.44GB | 0B |

**Total FF alloc (current snapshot):** 20.37GB  |  **24h avg:** 18.07GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2307 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.79MB | 65/2307 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1958/2307 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.65MB | 88/2307 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 22.78MB | 1958/2307 | `███░░░░░░░░░░░░ 26%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2307 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.51MB | 1436/2307 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2307 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2307 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2307 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2307 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2307 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2307 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2307 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2307 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2307 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2307 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 26.39GB | 824/2307 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 20.13GB | 1681/2307 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `reflect.growslice` | 18.13GB | 1519/2307 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.3x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.8x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.6x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
