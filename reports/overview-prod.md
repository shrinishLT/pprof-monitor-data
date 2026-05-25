# Overview: prod
*Last updated: 2026-05-25 17:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T17:03 (505 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,458 | avg: 15,600 | max: 84,644 | trend: decreasing (-1.03/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁▁▁▁▁▂▃▁▃▁▁▃▁▁
```

**Heap InUse** (current: 223.8MB | avg: 229.5MB | max: 1896.6MB | trend: stable (-0.10MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▃▃▅▃▄▃▂▄▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,458 | 14,403 | +55 | 15,600 | 84,644 | decreasing (-1.03/hr) |
| Heap InUse | 223.8MB | 264.5MB | -40.7MB | 229.5MB | 1896.6MB | stable (-0.10MB/hr) |
| Heap Sys | 6100.6MB | 6099.3MB | +1.3MB | 4174.6MB | 6883.9MB | |
| Heap Objects | 521,559 | 516,040 | +5519 | 985,857 | 8,100,802 | |

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
| 2026-05-25 | 35 | 15,482 | 235.7MB | 478.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 58.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `bytes.growSlice` | 5.52MB |
| 6 | `compress/flate.(*compressor).initDeflate` | 3.2MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 9 | `bufio.NewReaderSize` | 2.01MB |
| 10 | `reflect.unsafe_New` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 74.4GB |
| 2 | `reflect.growslice` | 28.97GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 28.44GB |
| 4 | `jackskj/carta.getUniqueId` | 25.55GB |
| 5 | `reflect.unsafe_New` | 22.71GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.76GB |
| 7 | `segmentio/kafka-go.makePartitions` | 16.98GB |
| 8 | `fmt.(*buffer).writeString` | 16.54GB |
| 9 | `carta/value.NewCell` | 16.49GB |
| 10 | `fmt.Sprintf` | 15.49GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 47.44MB | 20/505 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/505 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 503/505 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 29.69MB | 24/505 | `█████████░░░░░░ 62%` |
| 5 | `runtime.mallocgc` | 22.48MB | 503/505 | `███████░░░░░░░░ 47%` |
| 6 | `bytes.growSlice` | 13.5MB | 332/505 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/505 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/505 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/505 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/505 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/505 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/505 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/505 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.3GB | 480/505 | `██████░░░░░░░░░ 40%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/505 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/505 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/505 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.4GB | 437/505 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 18.01GB | 207/505 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.3GB | 305/505 | `█░░░░░░░░░░░░░░ 12%` |

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
