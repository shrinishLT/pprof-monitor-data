# Overview: prod
*Last updated: 2026-05-19 12:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T12:30 (186 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,760 | avg: 15,393 | max: 84,644 | trend: decreasing (-3.75/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄
```

**Heap InUse** (current: 432.3MB | avg: 229.6MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,760 | 14,233 | +5527 | 15,393 | 84,644 | decreasing (-3.75/hr) |
| Heap InUse | 432.3MB | 181.3MB | +251.0MB | 229.6MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 4940.8MB | 4950.0MB | -9.2MB | 4467.6MB | 6579.6MB | |
| Heap Objects | 2,062,536 | 930,050 | +1132486 | 984,636 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 26 | 15,263 | 225.2MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 40.2MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 20.22MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.58MB |
| 5 | `bufio.NewReaderSize` | 15.05MB |
| 6 | `bufio.NewWriterSize` | 11.04MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 7.01MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 3.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 57.92GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 34.58GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 34.52GB |
| 4 | `experiment/local.topologicalSort` | 22.98GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.44GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 10.88GB |
| 7 | `reflect.growslice` | 6.07GB |
| 8 | `jackskj/carta.getUniqueId` | 5.78GB |
| 9 | `fmt.Sprintf` | 5.17GB |
| 10 | `reflect.unsafe_New` | 4.85GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/186 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/186 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/186 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 184/186 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.26MB | 184/186 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/186 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/186 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.85MB | 16/186 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `bytes.growSlice` | 12.25MB | 110/186 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/186 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.27GB | 175/186 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.26GB | 181/186 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.16GB | 181/186 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 69.27GB | 176/186 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 50.42GB | 163/186 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.03GB | 131/186 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.16GB | 109/186 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/186 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 27.24GB | 46/186 | `███░░░░░░░░░░░░ 22%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/186 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
