# Overview: prod
*Last updated: 2026-05-16 02:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T02:03 (17 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 84,644 | avg: 18,557 | max: 84,644 | trend: INCREASING (+2803.60/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 1896.6MB | avg: 311.9MB | max: 1896.6MB | trend: INCREASING (+53.30MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

## Current Status

Goroutines: `████████████████████ 100%`
Heap InUse: `██████░░░░░░░░░░░░░░ 32%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 84,644 | 14,140 | +70504 | 18,557 | 84,644 | INCREASING (+2803.60/hr) |
| Heap InUse | 1896.6MB | 134.7MB | +1761.9MB | 311.9MB | 1896.6MB | INCREASING (+53.30MB/hr) |
| Heap Sys | 3461.2MB | 3683.5MB | -222.3MB | 4528.0MB | 5825.3MB | |
| Heap Objects | 8,100,802 | 377,899 | +7722903 | 1,227,473 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 7 | 24,622 | 415.4MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 317.04MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 158.73MB |
| 3 | `bufio.NewWriterSize` | 132.53MB |
| 4 | `bufio.NewReaderSize` | 131.0MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 53.55MB |
| 6 | `runtime.mallocgc` | 45.47MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB |
| 9 | `net/http.(*Transport).dialConn` | 30.0MB |
| 10 | `crypto/tls.Client` | 28.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 30.13GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 18.3GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 18.2GB |
| 4 | `experiment/local.topologicalSort` | 12.09GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.46GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 7.07GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 5.67GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.66GB |
| 9 | `fmt.Sprintf` | 4.91GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 3.25GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 82.13MB | 2/17 | `███████████████ 100%` |
| 2 | `bytes.growSlice` | 48.25MB | 7/17 | `████████░░░░░░░ 58%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 15/17 | `██████░░░░░░░░░ 44%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/17 | `█████░░░░░░░░░░ 37%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/17 | `█████░░░░░░░░░░ 36%` |
| 6 | `crypto/tls.Client` | 28.52MB | 1/17 | `█████░░░░░░░░░░ 34%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 19.52MB | 3/17 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bufio.NewReaderSize` | 16.91MB | 8/17 | `███░░░░░░░░░░░░ 20%` |
| 9 | `bufio.NewWriterSize` | 15.48MB | 9/17 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.19MB | 14/17 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 102.86GB | 12/17 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/17 | `██████░░░░░░░░░ 42%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/17 | `████░░░░░░░░░░░ 30%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 25.89GB | 11/17 | `███░░░░░░░░░░░░ 25%` |
| 5 | `internal/evaluation.mergeMetadata` | 13.8GB | 6/17 | `██░░░░░░░░░░░░░ 13%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 11.49GB | 12/17 | `█░░░░░░░░░░░░░░ 11%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 11.46GB | 12/17 | `█░░░░░░░░░░░░░░ 11%` |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/17 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/17 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 7.83GB | 9/17 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.6x avg)
