# Overview: prod
*Last updated: 2026-05-20 22:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T22:02 (253 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 48,719 | avg: 15,706 | max: 84,644 | trend: INCREASING (+12.34/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█
```

**Heap InUse** (current: 1004.2MB | avg: 235.8MB | max: 1896.6MB | trend: stable (+0.33MB/hr))
```
▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 57%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 48,719 | 20,265 | +28454 | 15,706 | 84,644 | INCREASING (+12.34/hr) |
| Heap InUse | 1004.2MB | 309.9MB | +694.3MB | 235.8MB | 1896.6MB | stable (+0.33MB/hr) |
| Heap Sys | 2812.8MB | 742.2MB | +2070.6MB | 4307.6MB | 6579.6MB | |
| Heap Objects | 3,352,310 | 1,041,543 | +2310767 | 1,000,982 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 45 | 17,153 | 260.4MB | 1004.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 187.91MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 87.4MB |
| 3 | `bufio.NewReaderSize` | 79.82MB |
| 4 | `bufio.NewWriterSize` | 63.24MB |
| 5 | `runtime.mallocgc` | 37.47MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 26.52MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 20.52MB |
| 9 | `net/http.(*Transport).dialConn` | 18.0MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 16.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 59.5GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 35.75GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 35.6GB |
| 4 | `experiment/local.topologicalSort` | 23.74GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.73GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 11.4GB |
| 7 | `reflect.growslice` | 7.41GB |
| 8 | `jackskj/carta.getUniqueId` | 6.7GB |
| 9 | `reflect.unsafe_New` | 6.13GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 5.84GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/253 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/253 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 251/253 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/253 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 23.96MB | 251/253 | `█████░░░░░░░░░░ 38%` |
| 6 | `bytes.growSlice` | 14.14MB | 166/253 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/253 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/253 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.95MB | 32/253 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/253 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.42GB | 242/253 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.12GB | 248/253 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.06GB | 248/253 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.14GB | 238/253 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.21GB | 230/253 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.06GB | 198/253 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.1GB | 175/253 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/253 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/253 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.37GB | 99/253 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
