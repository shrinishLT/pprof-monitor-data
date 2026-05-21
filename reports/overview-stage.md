# Overview: stage
*Last updated: 2026-05-21 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T18:02 (310 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,233 | avg: 14,332 | max: 28,205 | trend: INCREASING (+1.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 194.6MB | avg: 169.3MB | max: 732.9MB | trend: stable (+0.31MB/hr))
```
▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,233 | 14,141 | +92 | 14,332 | 28,205 | INCREASING (+1.58/hr) |
| Heap InUse | 194.6MB | 181.1MB | +13.5MB | 169.3MB | 732.9MB | stable (+0.31MB/hr) |
| Heap Sys | 1342.9MB | 1342.9MB | +0.0MB | 1307.9MB | 1793.6MB | |
| Heap Objects | 1,159,128 | 932,033 | +227095 | 869,629 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 54 | 14,431 | 180.1MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.55MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 1.5MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 6.3GB |
| 2 | `reflect.unsafe_NewArray` | 2.76GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 1.7GB |
| 4 | `reflect.MakeSlice` | 1.56GB |
| 5 | `fmt.Sprintf` | 1.46GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 753.11MB |
| 7 | `segmentio/kafka-go.makeLayout` | 714.2MB |
| 8 | `strconv.appendQuotedWith` | 675.06MB |
| 9 | `fmt.Sprint` | 661.43MB |
| 10 | `bytes.growSlice` | 454.65MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 308/310 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/310 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 304/310 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/310 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/310 | `█████░░░░░░░░░░ 35%` |
| 6 | `bytes.growSlice` | 11.91MB | 47/310 | `████░░░░░░░░░░░ 32%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/310 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/310 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/310 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/310 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 113.66GB | 301/310 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/310 | `█████████░░░░░░ 62%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/310 | `█████████░░░░░░ 62%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/310 | `█████████░░░░░░ 62%` |
| 5 | `reflect.unsafe_NewArray` | 49.1GB | 301/310 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.12GB | 286/310 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/310 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/310 | `████░░░░░░░░░░░ 31%` |
| 9 | `reflect.MakeSlice` | 27.53GB | 299/310 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.51GB | 286/310 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
