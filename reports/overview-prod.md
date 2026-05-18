# Overview: prod
*Last updated: 2026-05-18 13:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T13:33 (135 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,046 | avg: 15,267 | max: 84,644 | trend: decreasing (-24.02/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁
```

**Heap InUse** (current: 257.0MB | avg: 213.2MB | max: 1896.6MB | trend: decreasing (-1.40MB/hr))
```
▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,046 | 15,356 | -310 | 15,267 | 84,644 | decreasing (-24.02/hr) |
| Heap InUse | 257.0MB | 291.7MB | -34.7MB | 213.2MB | 1896.6MB | decreasing (-1.40MB/hr) |
| Heap Sys | 6170.7MB | 6169.2MB | +1.5MB | 4278.8MB | 6170.7MB | |
| Heap Objects | 785,216 | 889,073 | -103857 | 943,598 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 28 | 15,154 | 212.4MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewReaderSize` | 3.03MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `bufio.NewWriterSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 309.15GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 187.33GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 186.66GB |
| 4 | `experiment/local.topologicalSort` | 123.53GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 120.35GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 97.25GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 59.25GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 55.06GB |
| 9 | `reflect.growslice` | 31.32GB |
| 10 | `segmentio/kafka-go.makePartitions` | 29.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/135 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 133/135 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 21.96MB | 133/135 | `████████░░░░░░░ 59%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/135 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/135 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/135 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/135 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.49MB | 67/135 | `█████░░░░░░░░░░ 33%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.72MB | 7/135 | `████░░░░░░░░░░░ 31%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.96MB | 35/135 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.0GB | 128/135 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 52.88GB | 124/135 | `█████████████░░ 89%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 31.22GB | 130/135 | `███████░░░░░░░░ 52%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 31.21GB | 130/135 | `███████░░░░░░░░ 52%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.09GB | 126/135 | `██████░░░░░░░░░ 42%` |
| 6 | `fmt.(*buffer).writeString` | 24.13GB | 16/135 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.52GB | 80/135 | `█████░░░░░░░░░░ 38%` |
| 8 | `experiment/local.topologicalSort` | 22.33GB | 112/135 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.growslice` | 21.76GB | 43/135 | `█████░░░░░░░░░░ 36%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/135 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
