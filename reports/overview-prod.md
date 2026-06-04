# Overview: prod
*Last updated: 2026-06-04 15:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T15:00 (1135 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,267 | avg: 11,064 | max: 84,644 | trend: decreasing (-16.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 354.4MB | avg: 167.7MB | max: 2823.8MB | trend: stable (-0.20MB/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,267 | 17,510 | +757 | 11,064 | 84,644 | decreasing (-16.23/hr) |
| Heap InUse | 354.4MB | 276.2MB | +78.2MB | 167.7MB | 2823.8MB | stable (-0.20MB/hr) |
| Heap Sys | 3413.6MB | 3417.0MB | -3.4MB | 2632.2MB | 6883.9MB | |
| Heap Objects | 1,752,405 | 622,752 | +1129653 | 722,737 | 14,090,816 | |

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
| 2026-06-04 | 181 | 16,941 | 278.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.12MB |
| 3 | `bufio.NewReaderSize` | 11.04MB |
| 4 | `runtime.mallocgc` | 11.01MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewWriterSize` | 5.52MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.15GB |
| 2 | `fmt.Sprintf` | 7.04GB |
| 3 | `reflect.growslice` | 5.9GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.61GB |
| 5 | `jackskj/carta.getUniqueId` | 5.61GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.94GB |
| 7 | `reflect.unsafe_New` | 4.8GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.78GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.48GB |
| 10 | `carta/value.NewCell` | 3.45GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 438.95MB | 427.82MB | 231.97MB | 0B |
| `evaluation.mergeMetadata` | 224.06MB | 217.05MB | 122.81MB | 0B |
| `local.(*Client).EvaluateV2` | 672.74MB | 656.38MB | 350.33MB | 0B |
| `local.topologicalSort` | 94.10MB | 93.09MB | 48.26MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 629.33MB | 614.48MB | 332.15MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 105.82MB | 102.81MB | 50.40MB | 0B |
| `localEvaluation.getMapOfValue` | 629.33MB | 614.48MB | 332.15MB | 0B |
| `utils.ParseFeatureFlag` | 629.33MB | 614.48MB | 332.25MB | 0B |

**Total FF alloc (current snapshot):** 3.34GB  |  **24h avg:** 1.76GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1135 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1135 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 786/1135 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1135 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.22MB | 786/1135 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1135 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.4MB | 573/1135 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1135 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1135 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.45MB | 371/1135 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1135 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1135 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1135 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1135 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1135 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.97GB | 759/1135 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1135 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.62GB | 683/1135 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.54GB | 378/1135 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.21GB | 520/1135 | `█░░░░░░░░░░░░░░ 8%` |

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
