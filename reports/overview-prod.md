# Overview: prod
*Last updated: 2026-05-18 20:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T20:03 (153 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 23,165 | avg: 15,430 | max: 84,644 | trend: decreasing (-4.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅
```

**Heap InUse** (current: 670.7MB | avg: 228.1MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 27%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 23,165 | 18,394 | +4771 | 15,430 | 84,644 | decreasing (-4.37/hr) |
| Heap InUse | 670.7MB | 350.5MB | +320.2MB | 228.1MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 6557.4MB | 6573.6MB | -16.2MB | 4506.7MB | 6573.6MB | |
| Heap Objects | 2,919,198 | 1,075,837 | +1843361 | 986,494 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 46 | 15,739 | 262.2MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `bytes.growSlice` | 47.24MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 27.13MB |
| 5 | `bufio.NewWriterSize` | 20.59MB |
| 6 | `bufio.NewReaderSize` | 20.07MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 13.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 10 | `net/http.(*Transport).dialConn` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 467.21GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 283.01GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 281.99GB |
| 4 | `experiment/local.topologicalSort` | 186.68GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 146.59GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 140.32GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 89.22GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 64.13GB |
| 9 | `fmt.Sprintf` | 46.19GB |
| 10 | `segmentio/kafka-go.makePartitions` | 38.31GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/153 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 151/153 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 25.9MB | 151/153 | `██████████░░░░░ 70%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/153 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/153 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 13.17MB | 3/153 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 13.01MB | 85/153 | `█████░░░░░░░░░░ 35%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/153 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/153 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 49/153 | `████░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 95.75GB | 142/153 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 68.04GB | 146/153 | `██████████░░░░░ 71%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 56.22GB | 148/153 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 56.14GB | 148/153 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.91GB | 98/153 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 40.87GB | 130/153 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 29.51GB | 144/153 | `████░░░░░░░░░░░ 30%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 28.98GB | 77/153 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/153 | `███░░░░░░░░░░░░ 25%` |
| 10 | `fmt.Sprintf` | 22.89GB | 27/153 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
