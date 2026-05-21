# Overview: stage
*Last updated: 2026-05-21 17:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T17:32 (309 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,141 | avg: 14,332 | max: 28,205 | trend: INCREASING (+1.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 181.1MB | avg: 169.2MB | max: 732.9MB | trend: stable (+0.31MB/hr))
```
▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,141 | 14,068 | +73 | 14,332 | 28,205 | INCREASING (+1.61/hr) |
| Heap InUse | 181.1MB | 216.5MB | -35.4MB | 169.2MB | 732.9MB | stable (+0.31MB/hr) |
| Heap Sys | 1342.9MB | 1342.0MB | +0.9MB | 1307.8MB | 1793.6MB | |
| Heap Objects | 932,033 | 1,468,625 | -536592 | 868,692 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 53 | 14,435 | 179.8MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 5.29MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `reflect.unsafe_NewArray` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.05MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 5.54GB |
| 2 | `reflect.unsafe_NewArray` | 2.43GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 1.7GB |
| 4 | `fmt.Sprintf` | 1.45GB |
| 5 | `reflect.MakeSlice` | 1.36GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 751.11MB |
| 7 | `strconv.appendQuotedWith` | 674.06MB |
| 8 | `fmt.Sprint` | 659.92MB |
| 9 | `segmentio/kafka-go.makeLayout` | 635.44MB |
| 10 | `bytes.growSlice` | 452.14MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 307/309 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/309 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 303/309 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/309 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/309 | `█████░░░░░░░░░░ 35%` |
| 6 | `bytes.growSlice` | 11.91MB | 47/309 | `████░░░░░░░░░░░ 32%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/309 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/309 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/309 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/309 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 114.02GB | 300/309 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/309 | `█████████░░░░░░ 62%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/309 | `█████████░░░░░░ 62%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/309 | `█████████░░░░░░ 61%` |
| 5 | `reflect.unsafe_NewArray` | 49.26GB | 300/309 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.27GB | 285/309 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/309 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/309 | `████░░░░░░░░░░░ 31%` |
| 9 | `reflect.MakeSlice` | 27.61GB | 298/309 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.58GB | 285/309 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
