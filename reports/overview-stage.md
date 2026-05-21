# Overview: stage
*Last updated: 2026-05-21 16:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T16:30 (307 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,183 | avg: 14,334 | max: 28,205 | trend: INCREASING (+1.70/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁
```

**Heap InUse** (current: 178.1MB | avg: 169.0MB | max: 732.9MB | trend: stable (+0.31MB/hr))
```
▁▁▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,183 | 14,250 | -67 | 14,334 | 28,205 | INCREASING (+1.70/hr) |
| Heap InUse | 178.1MB | 191.0MB | -12.9MB | 169.0MB | 732.9MB | stable (+0.31MB/hr) |
| Heap Sys | 1341.4MB | 1340.8MB | +0.6MB | 1307.6MB | 1793.6MB | |
| Heap Objects | 849,415 | 1,020,604 | -171189 | 866,532 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 51 | 14,448 | 179.0MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bytes.growSlice` | 4.02MB |
| 7 | `bufio.NewReaderSize` | 2.55MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 3.88GB |
| 2 | `reflect.unsafe_NewArray` | 1.74GB |
| 3 | `fmt.Sprintf` | 1.41GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 1.4GB |
| 5 | `reflect.MakeSlice` | 985.02MB |
| 6 | `strconv.appendQuotedWith` | 654.01MB |
| 7 | `fmt.Sprint` | 636.36MB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 618.79MB |
| 9 | `segmentio/kafka-go.makeLayout` | 457.34MB |
| 10 | `bytes.growSlice` | 436.57MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 305/307 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/307 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 301/307 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/307 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/307 | `█████░░░░░░░░░░ 35%` |
| 6 | `bytes.growSlice` | 11.91MB | 47/307 | `████░░░░░░░░░░░ 32%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/307 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/307 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/307 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/307 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 114.75GB | 298/307 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/307 | `█████████░░░░░░ 62%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/307 | `█████████░░░░░░ 62%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/307 | `█████████░░░░░░ 61%` |
| 5 | `reflect.unsafe_NewArray` | 49.57GB | 298/307 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.6GB | 283/307 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/307 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/307 | `████░░░░░░░░░░░ 31%` |
| 9 | `reflect.MakeSlice` | 27.79GB | 296/307 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.72GB | 283/307 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
