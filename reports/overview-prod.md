# Overview: prod
*Last updated: 2026-06-04 14:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:50 (1133 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,493 | avg: 11,052 | max: 84,644 | trend: decreasing (-16.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 396.9MB | avg: 167.5MB | max: 2823.8MB | trend: stable (-0.21MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,493 | 19,124 | +369 | 11,052 | 84,644 | decreasing (-16.44/hr) |
| Heap InUse | 396.9MB | 355.3MB | +41.6MB | 167.5MB | 2823.8MB | stable (-0.21MB/hr) |
| Heap Sys | 3415.0MB | 3417.5MB | -2.5MB | 2630.8MB | 6883.9MB | |
| Heap Objects | 1,697,138 | 1,550,773 | +146365 | 721,917 | 14,090,816 | |

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
| 2026-06-04 | 179 | 16,931 | 278.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 35.73MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 19.09MB |
| 4 | `bufio.NewWriterSize` | 14.56MB |
| 5 | `bufio.NewReaderSize` | 14.55MB |
| 6 | `runtime.mallocgc` | 11.01MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.15GB |
| 2 | `fmt.Sprintf` | 6.61GB |
| 3 | `reflect.growslice` | 5.78GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.61GB |
| 5 | `jackskj/carta.getUniqueId` | 5.42GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.76GB |
| 7 | `reflect.unsafe_New` | 4.67GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.56GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.43GB |
| 10 | `fmt.(*buffer).writeString` | 3.36GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 416.15MB | 408.46MB | 229.11MB | 0B |
| `evaluation.mergeMetadata` | 212.55MB | 208.55MB | 121.36MB | 0B |
| `local.(*Client).EvaluateV2` | 638.52MB | 622.55MB | 346.26MB | 0B |
| `local.topologicalSort` | 91.08MB | 87.54MB | 47.82MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 598.08MB | 584.20MB | 329.94MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 99.79MB | 96.69MB | 48.18MB | 0B |
| `localEvaluation.getMapOfValue` | 598.08MB | 584.20MB | 329.94MB | 0B |
| `utils.ParseFeatureFlag` | 598.08MB | 584.20MB | 330.07MB | 0B |

**Total FF alloc (current snapshot):** 3.18GB  |  **24h avg:** 1.74GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1133 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1133 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 784/1133 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1133 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.25MB | 784/1133 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1133 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.37MB | 571/1133 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1133 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1133 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.44MB | 369/1133 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1133 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1133 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1133 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1133 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1133 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.04GB | 757/1133 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1133 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.66GB | 681/1133 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.57GB | 376/1133 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.23GB | 518/1133 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
