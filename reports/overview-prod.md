# Overview: prod
*Last updated: 2026-05-20 02:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T02:02 (213 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 25,220 | avg: 15,422 | max: 84,644 | trend: decreasing (-0.78/hr))
```
▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁▁▁▁▁▁▂▁▁▁▁▇
```

**Heap InUse** (current: 786.9MB | avg: 231.9MB | max: 1896.6MB | trend: stable (+0.21MB/hr))
```
▁▂▃▁▁▁▁▁▂▂▃▂▂▃▂▄▂▂▂▂▂▃▄▂▂▁▂▄▂▂▂▃▃▄▃▆▂▃▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▆▂▁▂▁▄▁▁▂▂▁▁▁▂▄▃▁▁▂▂▂▁▂▁▁▁▁▃▁▁▁▁█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 29%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 25,220 | 14,320 | +10900 | 15,422 | 84,644 | decreasing (-0.78/hr) |
| Heap InUse | 786.9MB | 154.3MB | +632.6MB | 231.9MB | 1896.6MB | stable (+0.21MB/hr) |
| Heap Sys | 4882.9MB | 4945.7MB | -62.8MB | 4527.8MB | 6579.6MB | |
| Heap Objects | 3,247,545 | 535,096 | +2712449 | 988,508 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 5 | 16,614 | 293.0MB | 786.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 58.8MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `internal/evaluation.mergeMetadata` | 36.51MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 25.62MB |
| 5 | `experiment/local.topologicalSort` | 25.36MB |
| 6 | `bufio.NewReaderSize` | 22.1MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 21.72MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 21.52MB |
| 9 | `runtime.mallocgc` | 20.22MB |
| 10 | `bufio.NewWriterSize` | 14.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 296.16GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 178.16GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 177.96GB |
| 4 | `experiment/local.topologicalSort` | 118.16GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 92.33GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 77.36GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 56.38GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 35.56GB |
| 9 | `fmt.Sprintf` | 30.04GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 23.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/213 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/213 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 211/213 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 34.92MB | 13/213 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.48MB | 211/213 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/213 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/213 | `███░░░░░░░░░░░░ 21%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.35MB | 23/213 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `bytes.growSlice` | 12.19MB | 133/213 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 208/213 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 126.74GB | 202/213 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.78GB | 208/213 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.7GB | 208/213 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.38GB | 203/213 | `███████░░░░░░░░ 52%` |
| 5 | `experiment/local.topologicalSort` | 53.17GB | 190/213 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.15GB | 158/213 | `█████░░░░░░░░░░ 38%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.18GB | 136/213 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.1GB | 194/213 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/213 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 23.63GB | 73/213 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
