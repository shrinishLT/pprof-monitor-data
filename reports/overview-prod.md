# Overview: prod
*Last updated: 2026-05-18 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T05:31 (119 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,683 | avg: 15,203 | max: 84,644 | trend: decreasing (-43.03/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 303.1MB | avg: 207.0MB | max: 1896.6MB | trend: decreasing (-2.80MB/hr))
```
▅█▅▂▃▃▃▃▅▃▂▄▄▂▂▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▂▂▃▂▁▂▂▁▂▆▅▃▅▂▃▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▂▁▁▁▁▁▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,683 | 14,385 | +1298 | 15,203 | 84,644 | decreasing (-43.03/hr) |
| Heap InUse | 303.1MB | 142.4MB | +160.7MB | 207.0MB | 1896.6MB | decreasing (-2.80MB/hr) |
| Heap Sys | 4691.3MB | 4699.0MB | -7.7MB | 4161.2MB | 5842.7MB | |
| Heap Objects | 1,625,921 | 685,233 | +940688 | 922,654 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 12 | 14,370 | 149.8MB | 303.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 17.0MB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 11.06MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `runtime.mallocgc` | 8.58MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 6.83MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `experiment/local.topologicalSort` | 4.05MB |
| 9 | `bufio.NewWriterSize` | 4.03MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 101.09GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 74.04GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 61.24GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 60.95GB |
| 5 | `experiment/local.topologicalSort` | 40.42GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 33.82GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.16GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 19.33GB |
| 9 | `segmentio/kafka-go.makePartitions` | 18.76GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 13.06GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 117/119 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 36.12MB | 6/119 | `██████████████░ 98%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/119 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.97MB | 117/119 | `████████░░░░░░░ 57%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/119 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 15.43MB | 7/119 | `██████░░░░░░░░░ 42%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/119 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.78MB | 53/119 | `█████░░░░░░░░░░ 34%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/119 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.37MB | 25/119 | `████░░░░░░░░░░░ 31%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 51.87GB | 112/119 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 32.78GB | 108/119 | `█████████░░░░░░ 63%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/119 | `██████░░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 21.5GB | 110/119 | `██████░░░░░░░░░ 41%` |
| 5 | `reflect.growslice` | 20.37GB | 36/119 | `█████░░░░░░░░░░ 39%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 19.63GB | 114/119 | `█████░░░░░░░░░░ 37%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 19.55GB | 114/119 | `█████░░░░░░░░░░ 37%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/119 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/119 | `████░░░░░░░░░░░ 30%` |
| 10 | `experiment/local.topologicalSort` | 13.5GB | 96/119 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
