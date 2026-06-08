# Overview: prod
*Last updated: 2026-06-09 01:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T01:50 (2416 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,749 | avg: 13,612 | max: 84,644 | trend: INCREASING (+4.23/hr))
```
▁▂█▃▂▃▂▁▃▁▁▁▁▁▁▂▃▃▁▂▃▇▄▅▃▃▇▄▂▅▃▂▃▁▂▂▁▃▃▂▁▁▁▁▃▂▁▂▆▃▁▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▁▃▂▁▂▁▁▂▁▁▁▁▁▂▂▁▁▁▂▁▁▁▁▁▂▂▁▁▇
```

**Heap InUse** (current: 426.0MB | avg: 211.3MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▃█▃▃▃▃▃▂▂▃▂▂▁▁▃▃▃▂▄▃▆▃▄▃▂▆▅▂▅▃▃▄▃▃▂▂▂▃▂▁▂▂▂▂▁▃▃▅▄▁▂▃▃▃▁▃▂▂▂▂▁▃▂▁▁▁▂▃▂▃▁▂▃▂▂▁▂▁▁▃▄▂▂▂▂▃▃▁▃▃▃▂▃▁▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,749 | 14,498 | +4251 | 13,612 | 84,644 | INCREASING (+4.23/hr) |
| Heap InUse | 426.0MB | 210.0MB | +216.0MB | 211.3MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3335.1MB | 3344.4MB | -9.3MB | 2426.0MB | 6883.9MB | |
| Heap Objects | 1,720,186 | 520,306 | +1199880 | 934,638 | 17,165,538 | |

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
| 2026-06-09 | 23 | 14,781 | 271.1MB | 426.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 33.76MB |
| 4 | `bufio.NewReaderSize` | 13.06MB |
| 5 | `bufio.NewWriterSize` | 10.54MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 82.84GB |
| 2 | `reflect.growslice` | 69.71GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 63.73GB |
| 4 | `jackskj/carta.getUniqueId` | 61.7GB |
| 5 | `reflect.unsafe_New` | 54.97GB |
| 6 | `fmt.Sprintf` | 46.62GB |
| 7 | `fmt.(*buffer).writeString` | 43.98GB |
| 8 | `reflect.unsafe_NewArray` | 42.34GB |
| 9 | `carta/value.NewCell` | 39.24GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 29.92GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.60GB | 3.60GB | 3.44GB | 0B |
| `evaluation.mergeMetadata` | 1.87GB | 1.87GB | 1.79GB | 0B |
| `local.(*Client).EvaluateV2` | 5.47GB | 5.46GB | 5.24GB | 0B |
| `local.topologicalSort` | 769.12MB | 768.10MB | 740.03MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.24GB | 5.23GB | 5.01GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 749.47MB | 749.47MB | 731.71MB | 0B |
| `localEvaluation.getMapOfValue` | 5.24GB | 5.23GB | 5.01GB | 0B |
| `utils.ParseFeatureFlag` | 5.25GB | 5.24GB | 5.01GB | 0B |

**Total FF alloc (current snapshot):** 28.14GB  |  **24h avg:** 26.94GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2416 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2416 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2067/2416 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 89/2416 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 24.24MB | 2067/2416 | `████░░░░░░░░░░░ 28%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2416 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.15MB | 1538/2416 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2416 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2416 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2416 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2416 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2416 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2416 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2416 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2416 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 30.36GB | 933/2416 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2416 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2416 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 23.57GB | 1790/2416 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `reflect.growslice` | 21.35GB | 1628/2416 | `██░░░░░░░░░░░░░ 17%` |

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
