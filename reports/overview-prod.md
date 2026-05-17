# Overview: prod
*Last updated: 2026-05-17 12:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-17T12:31 (85 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,825 | avg: 15,529 | max: 84,644 | trend: decreasing (-52.51/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 213.0MB | avg: 228.8MB | max: 1896.6MB | trend: decreasing (-3.34MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,825 | 15,214 | +611 | 15,529 | 84,644 | decreasing (-52.51/hr) |
| Heap InUse | 213.0MB | 202.7MB | +10.3MB | 228.8MB | 1896.6MB | decreasing (-3.34MB/hr) |
| Heap Sys | 1906.5MB | 293.5MB | +1613.0MB | 4355.5MB | 5842.7MB | |
| Heap Objects | 912,296 | 1,012,285 | -99989 | 996,208 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 26 | 15,138 | 192.4MB | 391.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.07MB |
| 3 | `runtime.mallocgc` | 13.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 5.02MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |
| 10 | `internal/evaluation.mergeMetadata` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 18.61GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 11.29GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 11.17GB |
| 4 | `experiment/local.topologicalSort` | 7.52GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.71GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.84GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 3.47GB |
| 8 | `reflect.growslice` | 1.92GB |
| 9 | `fmt.Sprintf` | 1.75GB |
| 10 | `jackskj/carta.getUniqueId` | 1.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 83/85 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.48MB | 5/85 | `██████████████░ 96%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/85 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 25.82MB | 83/85 | `██████████░░░░░ 70%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/85 | `███████░░░░░░░░ 50%` |
| 6 | `bytes.growSlice` | 15.63MB | 40/85 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 13.96MB | 19/85 | `█████░░░░░░░░░░ 38%` |
| 8 | `aes/gcm.NewGCMForTLS13` | 13.51MB | 6/85 | `█████░░░░░░░░░░ 36%` |
| 9 | `database/sql.convertAssignRows` | 13.33MB | 6/85 | `█████░░░░░░░░░░ 36%` |
| 10 | `crypto/tls.Client` | 13.01MB | 3/85 | `█████░░░░░░░░░░ 35%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.51GB | 78/85 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 30.73GB | 74/85 | `███████░░░░░░░░ 52%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/85 | `██████░░░░░░░░░ 41%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 23.37GB | 77/85 | `█████░░░░░░░░░░ 39%` |
| 5 | `reflect.growslice` | 20.87GB | 35/85 | `█████░░░░░░░░░░ 35%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 18.46GB | 80/85 | `████░░░░░░░░░░░ 31%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 18.33GB | 80/85 | `████░░░░░░░░░░░ 31%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/85 | `████░░░░░░░░░░░ 29%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.25GB | 3/85 | `████░░░░░░░░░░░ 27%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.98GB | 30/85 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
