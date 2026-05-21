# Overview: stage
*Last updated: 2026-05-22 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T03:31 (337 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,063 | avg: 14,317 | max: 28,205 | trend: INCREASING (+0.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 190.9MB | avg: 170.6MB | max: 732.9MB | trend: stable (+0.28MB/hr))
```
▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▂▁▂▂▁▂▁▂▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,063 | 14,283 | -220 | 14,317 | 28,205 | INCREASING (+0.73/hr) |
| Heap InUse | 190.9MB | 225.6MB | -34.7MB | 170.6MB | 732.9MB | stable (+0.28MB/hr) |
| Heap Sys | 1344.8MB | 1344.2MB | +0.6MB | 1310.8MB | 1793.6MB | |
| Heap Objects | 1,158,362 | 1,432,314 | -273952 | 881,876 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 72 | 14,362 | 180.0MB | 556.9MB |
| 2026-05-22 | 9 | 14,117 | 198.1MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.0MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `reflect.unsafe_NewArray` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 1.55MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 21.25GB |
| 2 | `reflect.unsafe_NewArray` | 9.31GB |
| 3 | `reflect.MakeSlice` | 5.21GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.62GB |
| 5 | `segmentio/kafka-go.makeLayout` | 2.29GB |
| 6 | `fmt.Sprintf` | 1.96GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 1.23GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 1.14GB |
| 9 | `internal/reflectlite.unsafe_New` | 1.03GB |
| 10 | `strconv.appendQuotedWith` | 926.86MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 335/337 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/337 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.54MB | 331/337 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/337 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/337 | `████░░░░░░░░░░░ 33%` |
| 6 | `bytes.growSlice` | 10.64MB | 54/337 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/337 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/337 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/337 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/337 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 105.4GB | 328/337 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/337 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/337 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/337 | `██████████░░░░░ 66%` |
| 5 | `reflect.unsafe_NewArray` | 45.54GB | 328/337 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.27GB | 313/337 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/337 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/337 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 25.52GB | 326/337 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.84GB | 313/337 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
