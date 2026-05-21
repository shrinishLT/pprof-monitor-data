# Overview: stage
*Last updated: 2026-05-21 15:06 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:06 (300 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 27,410 | avg: 14,331 | max: 28,205 | trend: INCREASING (+1.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 556.9MB | avg: 168.6MB | max: 732.9MB | trend: stable (+0.31MB/hr))
```
▁▁▁▂▁▁▁▁▁▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█
```

## Current Status

Goroutines: `███████████████████░ 97%`
Heap InUse: `██████░░░░░░░░░░░░░░ 31%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 27,410 | 14,248 | +13162 | 14,331 | 28,205 | INCREASING (+1.73/hr) |
| Heap InUse | 556.9MB | 149.9MB | +407.0MB | 168.6MB | 732.9MB | stable (+0.31MB/hr) |
| Heap Sys | 1149.1MB | 442.8MB | +706.3MB | 1308.5MB | 1793.6MB | |
| Heap Objects | 1,135,034 | 839,823 | +295211 | 865,790 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 44 | 14,450 | 177.5MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 133.15MB |
| 2 | `bufio.NewReaderSize` | 54.25MB |
| 3 | `bufio.NewWriterSize` | 51.71MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 46.72MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 22.02MB |
| 7 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB |
| 8 | `runtime.mallocgc` | 13.67MB |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.66GB |
| 2 | `reflect.unsafe_NewArray` | 756.57MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 752.47MB |
| 4 | `fmt.Sprintf` | 645.89MB |
| 5 | `reflect.MakeSlice` | 466.01MB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 341.73MB |
| 7 | `strconv.appendQuotedWith` | 307.44MB |
| 8 | `fmt.Sprint` | 280.36MB |
| 9 | `bytes.growSlice` | 201.02MB |
| 10 | `segmentio/kafka-go.makeLayout` | 196.34MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 298/300 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/300 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 294/300 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/300 | `█████░░░░░░░░░░ 38%` |
| 5 | `bytes.growSlice` | 13.17MB | 41/300 | `█████░░░░░░░░░░ 35%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/300 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/300 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/300 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/300 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/300 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 117.45GB | 291/300 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/300 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/300 | `█████████░░░░░░ 60%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/300 | `█████████░░░░░░ 60%` |
| 5 | `reflect.unsafe_NewArray` | 50.73GB | 291/300 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 48.78GB | 276/300 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/300 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/300 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.45GB | 289/300 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.24GB | 276/300 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
