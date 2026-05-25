# Overview: prod
*Last updated: 2026-05-25 14:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T14:03 (499 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,279 | avg: 15,595 | max: 84,644 | trend: decreasing (-1.19/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁▁▁▁▁▂▃▁
```

**Heap InUse** (current: 321.5MB | avg: 228.5MB | max: 1896.6MB | trend: stable (-0.13MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▃▃▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,279 | 19,434 | -4155 | 15,595 | 84,644 | decreasing (-1.19/hr) |
| Heap InUse | 321.5MB | 460.1MB | -138.6MB | 228.5MB | 1896.6MB | stable (-0.13MB/hr) |
| Heap Sys | 4826.5MB | 4820.1MB | +6.4MB | 4156.6MB | 6883.9MB | |
| Heap Objects | 1,467,649 | 1,701,551 | -233902 | 985,132 | 8,100,802 | |

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
| 2026-05-25 | 29 | 15,372 | 219.6MB | 478.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 58.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.06MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 6 | `bufio.NewReaderSize` | 4.02MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `bufio.NewWriterSize` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 65.66GB |
| 2 | `reflect.growslice` | 28.14GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 25.01GB |
| 4 | `jackskj/carta.getUniqueId` | 24.33GB |
| 5 | `reflect.unsafe_New` | 21.93GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.22GB |
| 7 | `fmt.(*buffer).writeString` | 16.01GB |
| 8 | `carta/value.NewCell` | 15.94GB |
| 9 | `segmentio/kafka-go.makePartitions` | 12.93GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.07GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 47.44MB | 20/499 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/499 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 497/499 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 29.69MB | 24/499 | `█████████░░░░░░ 62%` |
| 5 | `runtime.mallocgc` | 22.05MB | 497/499 | `██████░░░░░░░░░ 46%` |
| 6 | `bytes.growSlice` | 13.5MB | 326/499 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/499 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/499 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/499 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/499 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/499 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/499 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/499 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/499 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.05GB | 474/499 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/499 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/499 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.35GB | 431/499 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/499 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.3GB | 299/499 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
