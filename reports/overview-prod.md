# Overview: prod
*Last updated: 2026-06-12 18:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T18:06 (3474 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,478 | avg: 14,441 | max: 84,644 | trend: INCREASING (+3.41/hr))
```
▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 187.2MB | avg: 238.8MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,478 | 14,460 | +1018 | 14,441 | 84,644 | INCREASING (+3.41/hr) |
| Heap InUse | 187.2MB | 145.9MB | +41.3MB | 238.8MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 693.5MB | 693.7MB | -0.2MB | 2640.8MB | 6883.9MB | |
| Heap Objects | 566,992 | 555,278 | +11714 | 1,025,246 | 17,165,538 | |

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
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 218 | 16,155 | 271.3MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.7MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `runtime.mallocgc` | 8.01MB |
| 6 | `bufio.NewWriterSize` | 6.02MB |
| 7 | `bufio.NewReaderSize` | 4.52MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.38GB |
| 2 | `fmt.Sprintf` | 6.22GB |
| 3 | `jackskj/carta.getUniqueId` | 4.95GB |
| 4 | `reflect.growslice` | 4.87GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 4.44GB |
| 6 | `reflect.unsafe_NewArray` | 4.31GB |
| 7 | `reflect.unsafe_New` | 4.14GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.52GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.33GB |
| 10 | `fmt.Sprint` | 3.03GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 607.69MB | 600.57MB | 403.34MB | 0B |
| `evaluation.mergeMetadata` | 316.08MB | 312.08MB | 210.20MB | 0B |
| `local.(*Client).EvaluateV2` | 939.46MB | 926.66MB | 625.07MB | 0B |
| `local.topologicalSort` | 135.68MB | 132.62MB | 90.26MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 865.68MB | 853.43MB | 578.67MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 145.90MB | 144.85MB | 93.41MB | 0B |
| `localEvaluation.getMapOfValue` | 865.68MB | 853.43MB | 578.67MB | 0B |
| `utils.ParseFeatureFlag` | 869.18MB | 856.43MB | 580.70MB | 512.56kB |

**Total FF alloc (current snapshot):** 4.63GB  |  **24h avg:** 3.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.6MB | 68/3474 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.12MB | 94/3474 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3125/3474 | `██████████░░░░░ 69%` |
| 4 | `runtime.mallocgc` | 32.09MB | 3125/3474 | `█████████░░░░░░ 61%` |
| 5 | `database/sql.convertAssignRows` | 25.07MB | 117/3474 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3474 | `█████░░░░░░░░░░ 34%` |
| 7 | `bytes.growSlice` | 15.69MB | 2467/3474 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3474 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3474 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3474 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3474 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3474 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3474 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3474 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 63.74GB | 2686/3474 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.96GB | 2848/3474 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.47GB | 2702/3474 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 54.37GB | 2466/3474 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3474 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3474 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
