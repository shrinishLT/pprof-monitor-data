# Overview: prod
*Last updated: 2026-06-05 10:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:35 (1370 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 48,858 | avg: 11,892 | max: 84,644 | trend: decreasing (-3.15/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▅▄▅█
```

**Heap InUse** (current: 824.5MB | avg: 182.2MB | max: 3154.1MB | trend: stable (-0.01MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 57%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 48,858 | 36,994 | +11864 | 11,892 | 84,644 | decreasing (-3.15/hr) |
| Heap InUse | 824.5MB | 767.3MB | +57.2MB | 182.2MB | 3154.1MB | stable (-0.01MB/hr) |
| Heap Sys | 4294.2MB | 4340.7MB | -46.5MB | 2704.0MB | 6883.9MB | |
| Heap Objects | 1,799,415 | 3,321,574 | -1522159 | 810,733 | 17,165,538 | |

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
| 2026-06-05 | 128 | 15,885 | 259.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 165.87MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 70.83MB |
| 3 | `bufio.NewWriterSize` | 69.27MB |
| 4 | `bufio.NewReaderSize` | 64.74MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 27.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 24.52MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 12.51MB |
| 9 | `net/http.(*Transport).tryPutIdleConn` | 12.01MB |
| 10 | `net/http.(*Transport).dialConn` | 11.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 9.67GB |
| 2 | `jackskj/carta.getUniqueId` | 9.16GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 8.41GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 5 | `reflect.unsafe_New` | 7.88GB |
| 6 | `carta/value.NewCell` | 5.74GB |
| 7 | `fmt.(*buffer).writeString` | 5.73GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.97GB |
| 9 | `fmt.Sprintf` | 4.21GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 3.67GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 283.96MB | 274.86MB | 149.41MB | 0B |
| `evaluation.mergeMetadata` | 147.04MB | 141.54MB | 76.26MB | 0B |
| `local.(*Client).EvaluateV2` | 418.96MB | 408.33MB | 222.56MB | 0B |
| `local.topologicalSort` | 52.61MB | 52.11MB | 30.77MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 440.44MB | 429.79MB | 229.67MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 22.02MB | 21.52MB | 16.26MB | 0B |
| `localEvaluation.getMapOfValue` | 440.44MB | 429.79MB | 229.67MB | 0B |
| `utils.ParseFeatureFlag` | 440.44MB | 429.79MB | 229.73MB | 0B |

**Total FF alloc (current snapshot):** 2.19GB  |  **24h avg:** 1.16GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1370 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1370 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1370 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1021/1370 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.01MB | 1021/1370 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1370 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.78MB | 784/1370 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1370 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1370 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.29MB | 21/1370 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1370 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1370 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1370 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1370 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1370 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 33.98GB | 992/1370 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1370 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1370 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.41GB | 195/1370 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.4GB | 570/1370 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
