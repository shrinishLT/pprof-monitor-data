# Overview: prod
*Last updated: 2026-06-08 10:12 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T10:11 (2227 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 43,386 | avg: 13,328 | max: 84,644 | trend: INCREASING (+3.80/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇█
```

**Heap InUse** (current: 740.2MB | avg: 200.7MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▂▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂█▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 43,386 | 42,990 | +396 | 13,328 | 84,644 | INCREASING (+3.80/hr) |
| Heap InUse | 740.2MB | 928.7MB | -188.5MB | 200.7MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 3118.2MB | 3119.6MB | -1.4MB | 2353.1MB | 6883.9MB | |
| Heap Objects | 1,748,902 | 4,034,933 | -2286031 | 900,311 | 17,165,538 | |

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
| 2026-06-08 | 122 | 15,048 | 249.9MB | 928.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 145.93MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 73.34MB |
| 3 | `bufio.NewReaderSize` | 54.21MB |
| 4 | `bufio.NewWriterSize` | 52.2MB |
| 5 | `runtime.mallocgc` | 49.47MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 27.02MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 18.52MB |
| 9 | `crypto/tls.Client` | 14.51MB |
| 10 | `reflect.growslice` | 13.3MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 61.36GB |
| 2 | `reflect.growslice` | 53.88GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 50.38GB |
| 4 | `jackskj/carta.getUniqueId` | 45.48GB |
| 5 | `reflect.unsafe_New` | 41.42GB |
| 6 | `fmt.(*buffer).writeString` | 33.75GB |
| 7 | `reflect.unsafe_NewArray` | 31.38GB |
| 8 | `carta/value.NewCell` | 29.45GB |
| 9 | `fmt.Sprintf` | 23.79GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 21.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.78GB | 1.78GB | 1.63GB | 0B |
| `evaluation.mergeMetadata` | 941.23MB | 941.23MB | 864.57MB | 0B |
| `local.(*Client).EvaluateV2` | 2.70GB | 2.70GB | 2.48GB | 0B |
| `local.topologicalSort` | 369.59MB | 369.59MB | 337.72MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.71GB | 2.71GB | 2.48GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 261.76MB | 261.76MB | 250.91MB | 0B |
| `localEvaluation.getMapOfValue` | 2.71GB | 2.71GB | 2.48GB | 0B |
| `utils.ParseFeatureFlag` | 2.72GB | 2.72GB | 2.48GB | 0B |

**Total FF alloc (current snapshot):** 14.15GB  |  **24h avg:** 12.97GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.58MB | 38/2227 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2227 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1878/2227 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.29MB | 87/2227 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 21.59MB | 1878/2227 | `███░░░░░░░░░░░░ 25%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2227 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.38MB | 1362/2227 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.42MB | 38/2227 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2227 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `crypto/tls.Client` | 10.55MB | 56/2227 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2227 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2227 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2227 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2227 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2227 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2227 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2227 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 22.99GB | 744/2227 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `segmentio/kafka-go.makePartitions` | 17.84GB | 1601/2227 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `reflect.growslice` | 15.66GB | 1439/2227 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.3x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.9x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
