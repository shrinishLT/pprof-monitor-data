# Overview: prod
*Last updated: 2026-06-06 01:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T01:10 (1544 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,571 | avg: 12,381 | max: 84,644 | trend: INCREASING (+1.12/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▄▄▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄
```

**Heap InUse** (current: 421.4MB | avg: 187.8MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▁▁▁▂▁▁▂▁▁▁▁▂▁▁▂▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▂▃▁▁▁▂▂▂▁▃▃▂▂▁▁▁▁▂▄▅▁▄▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▆█▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,571 | 26,442 | -6871 | 12,381 | 84,644 | INCREASING (+1.12/hr) |
| Heap InUse | 421.4MB | 563.5MB | -142.1MB | 187.8MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 1013.1MB | 1013.9MB | -0.8MB | 2529.7MB | 6883.9MB | |
| Heap Objects | 1,137,751 | 955,122 | +182629 | 832,217 | 17,165,538 | |

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
| 2026-06-06 | 15 | 18,291 | 331.2MB | 563.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 39.2MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewWriterSize` | 19.1MB |
| 4 | `bufio.NewReaderSize` | 19.09MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.07MB |
| 6 | `runtime.mallocgc` | 15.63MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 22.14GB |
| 2 | `segmentio/kafka-go.makePartitions` | 18.82GB |
| 3 | `jackskj/carta.getUniqueId` | 15.13GB |
| 4 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 15.09GB |
| 5 | `reflect.growslice` | 14.22GB |
| 6 | `reflect.unsafe_New` | 12.49GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.96GB |
| 8 | `fmt.Sprint` | 10.67GB |
| 9 | `strconv.appendQuotedWith` | 10.65GB |
| 10 | `fmt.(*buffer).writeString` | 9.98GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.22GB | 1.22GB | 1.09GB | 0B |
| `evaluation.mergeMetadata` | 651.16MB | 649.66MB | 574.28MB | 0B |
| `local.(*Client).EvaluateV2` | 1.88GB | 1.87GB | 1.68GB | 0B |
| `local.topologicalSort` | 274.28MB | 273.27MB | 246.06MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.78GB | 1.78GB | 1.58GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 277.52MB | 277.52MB | 258.81MB | 0B |
| `localEvaluation.getMapOfValue` | 1.78GB | 1.78GB | 1.58GB | 0B |
| `utils.ParseFeatureFlag` | 1.79GB | 1.78GB | 1.58GB | 0B |

**Total FF alloc (current snapshot):** 9.63GB  |  **24h avg:** 8.56GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1544 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1544 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1544 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1195/1544 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1544 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.14MB | 1195/1544 | `██░░░░░░░░░░░░░ 17%` |
| 7 | `bytes.growSlice` | 14.96MB | 938/1544 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1544 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1544 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1544 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1544 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1544 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1544 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1544 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1544 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1544 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1544 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1544 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.76GB | 256/1544 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.52GB | 728/1544 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
