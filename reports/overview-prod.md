# Overview: prod
*Last updated: 2026-06-09 02:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T02:55 (2429 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 23,887 | avg: 13,627 | max: 84,644 | trend: INCREASING (+4.24/hr))
```
▁▁▁▂▂▁▁▂▄▂▃▂▂▄▂▁▃▂▁▂▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▅▃▃▂▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 527.1MB | avg: 211.9MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▁▃▃▃▂▄▃▆▃▄▃▂▆▅▂▅▃▂▄▃▃▂▂▂▃▂▁▂▂▂▂▂▃▃▅▄▁▂▃▂▃▁▃▂▂▂▂▂▃▂▁▁▁▂▃▂▃▁▂▃▂▂▁▂▁▁▃▃▂▂▂▂▂▃▁▃▃▃▂▃▁▅▆▃▃▄▃▃▂▂▂▁▃▁█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 28%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 23,887 | 14,213 | +9674 | 13,627 | 84,644 | INCREASING (+4.24/hr) |
| Heap InUse | 527.1MB | 186.6MB | +340.5MB | 211.9MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3316.2MB | 3331.1MB | -14.9MB | 2430.8MB | 6883.9MB | |
| Heap Objects | 1,513,818 | 554,256 | +959562 | 935,239 | 17,165,538 | |

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
| 2026-06-09 | 36 | 15,319 | 285.4MB | 527.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 61.1MB |
| 2 | `runtime.mallocgc` | 50.47MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.12MB |
| 5 | `bufio.NewWriterSize` | 20.11MB |
| 6 | `bufio.NewReaderSize` | 20.09MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 9.01MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 7.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 84.27GB |
| 2 | `reflect.growslice` | 74.19GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.22GB |
| 4 | `jackskj/carta.getUniqueId` | 66.44GB |
| 5 | `reflect.unsafe_New` | 58.88GB |
| 6 | `fmt.Sprintf` | 52.98GB |
| 7 | `fmt.(*buffer).writeString` | 47.46GB |
| 8 | `reflect.unsafe_NewArray` | 43.13GB |
| 9 | `carta/value.NewCell` | 42.0GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 37.3GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.67GB | 3.66GB | 3.53GB | 0B |
| `evaluation.mergeMetadata` | 1.91GB | 1.91GB | 1.83GB | 0B |
| `local.(*Client).EvaluateV2` | 5.57GB | 5.56GB | 5.36GB | 0B |
| `local.topologicalSort` | 783.81MB | 782.80MB | 755.32MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.34GB | 5.33GB | 5.13GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 755.67MB | 754.62MB | 741.13MB | 0B |
| `localEvaluation.getMapOfValue` | 5.34GB | 5.33GB | 5.13GB | 0B |
| `utils.ParseFeatureFlag` | 5.35GB | 5.34GB | 5.14GB | 0B |

**Total FF alloc (current snapshot):** 28.68GB  |  **24h avg:** 27.59GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2429 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2429 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2080/2429 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2429 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 24.4MB | 2080/2429 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2429 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.17MB | 1550/2429 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2429 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2429 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2429 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2429 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2429 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2429 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2429 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2429 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 30.88GB | 946/2429 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2429 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2429 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 24.01GB | 1803/2429 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `reflect.growslice` | 21.76GB | 1641/2429 | `██░░░░░░░░░░░░░ 17%` |

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
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
