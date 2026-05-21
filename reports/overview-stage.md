# Overview: stage
*Last updated: 2026-05-21 16:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T16:02 (306 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,250 | avg: 14,334 | max: 28,205 | trend: INCREASING (+1.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁
```

**Heap InUse** (current: 191.0MB | avg: 169.0MB | max: 732.9MB | trend: stable (+0.31MB/hr))
```
▁▁▁▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,250 | 14,267 | -17 | 14,334 | 28,205 | INCREASING (+1.73/hr) |
| Heap InUse | 191.0MB | 220.5MB | -29.5MB | 169.0MB | 732.9MB | stable (+0.31MB/hr) |
| Heap Sys | 1340.8MB | 1340.2MB | +0.6MB | 1307.4MB | 1793.6MB | |
| Heap Objects | 1,020,604 | 1,330,206 | -309602 | 866,588 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 50 | 14,453 | 179.1MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bytes.growSlice` | 2.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.05MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `runtime/pprof.(*profileBuilder).emitLocation` | 1.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 3.15GB |
| 2 | `reflect.unsafe_NewArray` | 1.4GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 1.4GB |
| 4 | `fmt.Sprintf` | 1.37GB |
| 5 | `reflect.MakeSlice` | 802.02MB |
| 6 | `strconv.appendQuotedWith` | 639.97MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 617.78MB |
| 8 | `fmt.Sprint` | 614.3MB |
| 9 | `bytes.growSlice` | 424.02MB |
| 10 | `segmentio/kafka-go.makeLayout` | 377.51MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 304/306 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/306 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 300/306 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/306 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/306 | `█████░░░░░░░░░░ 35%` |
| 6 | `bytes.growSlice` | 12.09MB | 46/306 | `████░░░░░░░░░░░ 33%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/306 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/306 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/306 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/306 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 115.13GB | 297/306 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/306 | `█████████░░░░░░ 62%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/306 | `█████████░░░░░░ 61%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/306 | `█████████░░░░░░ 61%` |
| 5 | `reflect.unsafe_NewArray` | 49.73GB | 297/306 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.76GB | 282/306 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/306 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/306 | `████░░░░░░░░░░░ 31%` |
| 9 | `reflect.MakeSlice` | 27.88GB | 295/306 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.8GB | 282/306 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
