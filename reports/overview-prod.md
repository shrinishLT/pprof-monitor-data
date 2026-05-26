# Overview: prod
*Last updated: 2026-05-26 18:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T18:01 (553 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,263 | avg: 15,620 | max: 84,644 | trend: stable (-0.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▃
```

**Heap InUse** (current: 412.4MB | avg: 230.2MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂▄▄▅▃▄▃▂▅▃▂▄▃▃▅▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▃▁▁▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,263 | 14,825 | +5438 | 15,620 | 84,644 | stable (-0.35/hr) |
| Heap InUse | 412.4MB | 163.2MB | +249.2MB | 230.2MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 3449.1MB | 3457.1MB | -8.0MB | 4158.4MB | 6883.9MB | |
| Heap Objects | 1,605,136 | 613,943 | +991193 | 984,905 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 35 | 16,011 | 219.5MB | 639.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 39.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 16.58MB |
| 4 | `runtime.mallocgc` | 15.51MB |
| 5 | `bufio.NewWriterSize` | 14.57MB |
| 6 | `bufio.NewReaderSize` | 14.05MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 9.51MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 17.09GB |
| 2 | `fmt.Sprintf` | 11.06GB |
| 3 | `segmentio/kafka-go.makePartitions` | 9.16GB |
| 4 | `jackskj/carta.getUniqueId` | 8.29GB |
| 5 | `reflect.growslice` | 8.26GB |
| 6 | `reflect.unsafe_New` | 7.24GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 6.58GB |
| 8 | `strconv.appendQuotedWith` | 5.39GB |
| 9 | `fmt.Sprint` | 5.37GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 5.21GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 48.86MB | 21/553 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/553 | `██████████████░ 96%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 551/553 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.37MB | 27/553 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 22.89MB | 551/553 | `███████░░░░░░░░ 46%` |
| 6 | `bytes.growSlice` | 13.46MB | 370/553 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/553 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/553 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/553 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/553 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/553 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/553 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/553 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/553 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.33GB | 528/553 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/553 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/553 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.67GB | 484/553 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 17.54GB | 232/553 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.72GB | 345/553 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
