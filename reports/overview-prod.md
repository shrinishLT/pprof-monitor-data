# Overview: prod
*Last updated: 2026-05-22 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T10:30 (348 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 47,840 | avg: 15,828 | max: 84,644 | trend: INCREASING (+8.55/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇
```

**Heap InUse** (current: 962.7MB | avg: 243.7MB | max: 1896.6MB | trend: stable (+0.34MB/hr))
```
█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁▇
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 56%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 47,840 | 15,694 | +32146 | 15,828 | 84,644 | INCREASING (+8.55/hr) |
| Heap InUse | 962.7MB | 240.0MB | +722.7MB | 243.7MB | 1896.6MB | stable (+0.34MB/hr) |
| Heap Sys | 4948.5MB | 5062.1MB | -113.6MB | 4322.0MB | 6579.6MB | |
| Heap Objects | 3,203,634 | 845,320 | +2358314 | 1,016,083 | 8,100,802 | |

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
| 2026-05-22 | 24 | 16,492 | 264.4MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 149.23MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 79.36MB |
| 3 | `bufio.NewWriterSize` | 66.27MB |
| 4 | `bufio.NewReaderSize` | 63.77MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 35.36MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 25.02MB |
| 8 | `internal/evaluation.mergeMetadata` | 22.01MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 20.52MB |
| 10 | `crypto/tls.Client` | 18.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 449.47GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 269.66GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 269.28GB |
| 4 | `experiment/local.topologicalSort` | 178.36GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 140.61GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 118.36GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 85.57GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 51.03GB |
| 9 | `fmt.Sprintf` | 44.37GB |
| 10 | `segmentio/kafka-go.makePartitions` | 32.49GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/348 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/348 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 346/348 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/348 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.82MB | 346/348 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 14.37MB | 245/348 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/348 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/348 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.98MB | 50/348 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/348 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 134.58GB | 337/348 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.87GB | 343/348 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.86GB | 343/348 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 55.23GB | 325/348 | `██████░░░░░░░░░ 41%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 54.68GB | 324/348 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.66GB | 293/348 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.75GB | 269/348 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.49GB | 287/348 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/348 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `fmt.Sprintf` | 19.97GB | 172/348 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
