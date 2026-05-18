# Overview: prod
*Last updated: 2026-05-18 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T19:31 (152 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,394 | avg: 15,379 | max: 84,644 | trend: decreasing (-8.51/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃
```

**Heap InUse** (current: 350.5MB | avg: 225.2MB | max: 1896.6MB | trend: stable (-0.13MB/hr))
```
▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▁▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆▄▄▃▅▅▆▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,394 | 19,578 | -1184 | 15,379 | 84,644 | decreasing (-8.51/hr) |
| Heap InUse | 350.5MB | 408.4MB | -57.9MB | 225.2MB | 1896.6MB | stable (-0.13MB/hr) |
| Heap Sys | 6573.6MB | 6168.8MB | +404.8MB | 4493.2MB | 6573.6MB | |
| Heap Objects | 1,075,837 | 1,347,490 | -271653 | 973,779 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 45 | 15,574 | 253.2MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 26.64MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.56MB |
| 5 | `bufio.NewWriterSize` | 10.55MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewReaderSize` | 8.03MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 433.71GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 262.73GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 261.96GB |
| 4 | `experiment/local.topologicalSort` | 173.29GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 140.3GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 136.05GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 82.91GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 64.13GB |
| 9 | `fmt.Sprintf` | 42.36GB |
| 10 | `segmentio/kafka-go.makePartitions` | 37.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/152 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 150/152 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 25.71MB | 150/152 | `██████████░░░░░ 69%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/152 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/152 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/152 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 12.61MB | 84/152 | `█████░░░░░░░░░░ 34%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/152 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/152 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.45MB | 48/152 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 93.12GB | 141/152 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 67.54GB | 145/152 | `██████████░░░░░ 72%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 54.68GB | 147/152 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 54.6GB | 147/152 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 39.82GB | 97/152 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 39.74GB | 129/152 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 29.27GB | 143/152 | `████░░░░░░░░░░░ 31%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.18GB | 76/152 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/152 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.growslice` | 22.61GB | 47/152 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
