# Overview: prod
*Last updated: 2026-05-21 03:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T03:30 (264 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,618 | avg: 15,709 | max: 84,644 | trend: INCREASING (+11.01/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 224.0MB | avg: 237.1MB | max: 1896.6MB | trend: stable (+0.35MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,618 | 17,806 | -1188 | 15,709 | 84,644 | INCREASING (+11.01/hr) |
| Heap InUse | 224.0MB | 344.5MB | -120.5MB | 237.1MB | 1896.6MB | stable (+0.35MB/hr) |
| Heap Sys | 747.3MB | 5106.0MB | -4358.7MB | 4306.3MB | 6579.6MB | |
| Heap Objects | 884,893 | 1,407,822 | -522929 | 996,635 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 8 | 15,943 | 288.1MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 23.62MB |
| 3 | `runtime.mallocgc` | 14.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.04MB |
| 6 | `bufio.NewWriterSize` | 5.02MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 3.0MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.7GB |
| 2 | `internal/evaluation.mergeMetadata` | 1.18GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 821.69MB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 741.92MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 717.65MB |
| 6 | `experiment/local.topologicalSort` | 468.35MB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 387.63MB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 309.11MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 278.51MB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 260.05MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/264 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.44MB | 13/264 | `██████████░░░░░ 69%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 262/264 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.87MB | 15/264 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 24.44MB | 262/264 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 14.05MB | 177/264 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/264 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/264 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/264 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.63MB | 36/264 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.3GB | 253/264 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.5GB | 259/264 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.45GB | 259/264 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 59.01GB | 244/264 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.65GB | 241/264 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.28GB | 209/264 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.57GB | 185/264 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.73GB | 223/264 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/264 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.59GB | 108/264 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
