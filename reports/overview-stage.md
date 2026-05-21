# Overview: stage
*Last updated: 2026-05-21 15:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:30 (302 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,824 | avg: 14,332 | max: 28,205 | trend: INCREASING (+1.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁
```

**Heap InUse** (current: 177.7MB | avg: 168.6MB | max: 732.9MB | trend: stable (+0.30MB/hr))
```
▁▂▁▁▁▁▁▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,824 | 14,108 | +716 | 14,332 | 28,205 | INCREASING (+1.73/hr) |
| Heap InUse | 177.7MB | 160.1MB | +17.6MB | 168.6MB | 732.9MB | stable (+0.30MB/hr) |
| Heap Sys | 1212.9MB | 1208.7MB | +4.2MB | 1307.9MB | 1793.6MB | |
| Heap Objects | 454,869 | 783,157 | -328288 | 864,155 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 46 | 14,450 | 177.1MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `bytes.growSlice` | 4.53MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewReaderSize` | 3.05MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 2.32GB |
| 2 | `fmt.Sprintf` | 1.3GB |
| 3 | `reflect.unsafe_NewArray` | 1.04GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 752.47MB |
| 5 | `reflect.MakeSlice` | 622.51MB |
| 6 | `strconv.appendQuotedWith` | 611.9MB |
| 7 | `fmt.Sprint` | 591.76MB |
| 8 | `bytes.growSlice` | 402.41MB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 341.73MB |
| 10 | `segmentio/kafka-go.makeLayout` | 274.16MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 300/302 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/302 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 296/302 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/302 | `█████░░░░░░░░░░ 38%` |
| 5 | `bytes.growSlice` | 12.96MB | 42/302 | `█████░░░░░░░░░░ 35%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/302 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/302 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/302 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/302 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/302 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 116.66GB | 293/302 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/302 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/302 | `█████████░░░░░░ 61%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/302 | `█████████░░░░░░ 60%` |
| 5 | `reflect.unsafe_NewArray` | 50.39GB | 293/302 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 48.43GB | 278/302 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/302 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/302 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.26GB | 291/302 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.09GB | 278/302 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
