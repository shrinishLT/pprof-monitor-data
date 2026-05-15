# Overview: prod
*Last updated: 2026-05-16 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T03:31 (20 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,552 | avg: 18,278 | max: 84,644 | trend: INCREASING (+1596.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁
```

**Heap InUse** (current: 433.8MB | avg: 313.6MB | max: 1896.6MB | trend: INCREASING (+34.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,552 | 15,312 | +5240 | 18,278 | 84,644 | INCREASING (+1596.36/hr) |
| Heap InUse | 433.8MB | 303.4MB | +130.4MB | 313.6MB | 1896.6MB | INCREASING (+34.18MB/hr) |
| Heap Sys | 5742.2MB | 4755.1MB | +987.1MB | 4611.2MB | 5825.3MB | |
| Heap Objects | 1,472,178 | 1,253,730 | +218448 | 1,225,474 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 10 | 22,244 | 387.8MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 36.24MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.58MB |
| 5 | `bufio.NewWriterSize` | 15.61MB |
| 6 | `bufio.NewReaderSize` | 11.57MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 10 | `crypto/tls.Client` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 41.53GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 25.28GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 25.18GB |
| 4 | `experiment/local.topologicalSort` | 16.65GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 16.02GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.07GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 7.87GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 7.24GB |
| 9 | `fmt.Sprintf` | 7.22GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.68GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 46.97MB | 4/20 | `███████████████ 100%` |
| 2 | `bytes.growSlice` | 42.62MB | 9/20 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 18/20 | `███████████░░░░ 77%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/20 | `█████████░░░░░░ 64%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/20 | `█████████░░░░░░ 63%` |
| 6 | `runtime.mallocgc` | 17.21MB | 18/20 | `█████░░░░░░░░░░ 36%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/20 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/20 | `█████░░░░░░░░░░ 35%` |
| 9 | `bufio.NewReaderSize` | 16.32MB | 9/20 | `█████░░░░░░░░░░ 34%` |
| 10 | `bufio.NewWriterSize` | 13.33MB | 12/20 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 84.83GB | 15/20 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/20 | `███████░░░░░░░░ 51%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/20 | `█████░░░░░░░░░░ 37%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.57GB | 14/20 | `███░░░░░░░░░░░░ 25%` |
| 5 | `internal/evaluation.mergeMetadata` | 21.39GB | 9/20 | `███░░░░░░░░░░░░ 25%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 13.64GB | 15/20 | `██░░░░░░░░░░░░░ 16%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 13.6GB | 15/20 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/20 | `█░░░░░░░░░░░░░░ 10%` |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/20 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `experiment/local.topologicalSort` | 8.6GB | 9/20 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.6x avg)
