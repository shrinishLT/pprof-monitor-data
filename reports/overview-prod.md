# Overview: prod
*Last updated: 2026-05-18 19:04 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T19:03 (150 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,920 | avg: 15,331 | max: 84,644 | trend: decreasing (-12.75/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃
```

**Heap InUse** (current: 378.3MB | avg: 223.1MB | max: 1896.6MB | trend: stable (-0.30MB/hr))
```
▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▁▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆▄▄▃▅▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,920 | 15,972 | +2948 | 15,331 | 84,644 | decreasing (-12.75/hr) |
| Heap InUse | 378.3MB | 370.1MB | +8.2MB | 223.1MB | 1896.6MB | stable (-0.30MB/hr) |
| Heap Sys | 6168.4MB | 6170.2MB | -1.8MB | 4468.2MB | 6179.8MB | |
| Heap Objects | 1,284,179 | 1,670,144 | -385965 | 970,607 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 43 | 15,415 | 247.3MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 21.61MB |
| 4 | `bufio.NewWriterSize` | 17.08MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 15.07MB |
| 6 | `bufio.NewReaderSize` | 12.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 423.5GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 256.48GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 255.75GB |
| 4 | `experiment/local.topologicalSort` | 169.17GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 132.82GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 80.97GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.91GB |
| 9 | `fmt.Sprintf` | 41.07GB |
| 10 | `segmentio/kafka-go.makePartitions` | 36.97GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/150 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 148/150 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 25.31MB | 148/150 | `██████████░░░░░ 68%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/150 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/150 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/150 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 12.28MB | 82/150 | `█████░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/150 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/150 | `████░░░░░░░░░░░ 28%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/150 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 88.29GB | 139/150 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 66.55GB | 143/150 | `███████████░░░░ 75%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 51.85GB | 145/150 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 51.78GB | 145/150 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 37.83GB | 95/150 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 37.67GB | 127/150 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 28.79GB | 141/150 | `████░░░░░░░░░░░ 32%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.73GB | 74/150 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/150 | `████░░░░░░░░░░░ 27%` |
| 10 | `reflect.growslice` | 22.61GB | 47/150 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
