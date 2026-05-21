# Overview: stage
*Last updated: 2026-05-21 16:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T16:00 (305 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,267 | avg: 14,335 | max: 28,205 | trend: INCREASING (+1.76/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁
```

**Heap InUse** (current: 220.5MB | avg: 168.9MB | max: 732.9MB | trend: stable (+0.31MB/hr))
```
▁▁▁▁▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,267 | 14,595 | -328 | 14,335 | 28,205 | INCREASING (+1.76/hr) |
| Heap InUse | 220.5MB | 195.7MB | +24.8MB | 168.9MB | 732.9MB | stable (+0.31MB/hr) |
| Heap Sys | 1340.2MB | 1213.8MB | +126.4MB | 1307.3MB | 1793.6MB | |
| Heap Objects | 1,330,206 | 926,532 | +403674 | 866,083 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 49 | 14,457 | 178.8MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `bufio.NewReaderSize` | 2.55MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `bufio.NewWriterSize` | 1.52MB |
| 9 | `bytes.growSlice` | 1.01MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 3.11GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 1.4GB |
| 3 | `reflect.unsafe_NewArray` | 1.39GB |
| 4 | `fmt.Sprintf` | 1.36GB |
| 5 | `reflect.MakeSlice` | 792.52MB |
| 6 | `strconv.appendQuotedWith` | 639.47MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 617.78MB |
| 8 | `fmt.Sprint` | 612.8MB |
| 9 | `bytes.growSlice` | 423.01MB |
| 10 | `segmentio/kafka-go.makeLayout` | 372.94MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 303/305 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/305 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 299/305 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/305 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/305 | `█████░░░░░░░░░░ 35%` |
| 6 | `bytes.growSlice` | 12.3MB | 45/305 | `█████░░░░░░░░░░ 33%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/305 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/305 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/305 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/305 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 115.5GB | 296/305 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/305 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/305 | `█████████░░░░░░ 61%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/305 | `█████████░░░░░░ 61%` |
| 5 | `reflect.unsafe_NewArray` | 49.9GB | 296/305 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 47.93GB | 281/305 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/305 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/305 | `████░░░░░░░░░░░ 31%` |
| 9 | `reflect.MakeSlice` | 27.98GB | 294/305 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.87GB | 281/305 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
