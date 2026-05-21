# Overview: stage
*Last updated: 2026-05-21 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T18:31 (312 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,115 | avg: 14,330 | max: 28,205 | trend: INCREASING (+1.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 193.0MB | avg: 169.5MB | max: 732.9MB | trend: stable (+0.31MB/hr))
```
▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,115 | 14,073 | +42 | 14,330 | 28,205 | INCREASING (+1.49/hr) |
| Heap InUse | 193.0MB | 210.2MB | -17.2MB | 169.5MB | 732.9MB | stable (+0.31MB/hr) |
| Heap Sys | 1343.0MB | 1343.1MB | -0.1MB | 1308.1MB | 1793.6MB | |
| Heap Objects | 1,068,930 | 1,381,022 | -312092 | 871,907 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 56 | 14,419 | 180.8MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.5MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `reflect.unsafe_NewArray` | 3.0MB |
| 8 | `bufio.NewReaderSize` | 2.57MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `kafka-go/protocol.newPage` | 2.13MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.05GB |
| 2 | `reflect.unsafe_NewArray` | 3.08GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 2.14GB |
| 4 | `reflect.MakeSlice` | 1.74GB |
| 5 | `fmt.Sprintf` | 1.48GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 953.72MB |
| 7 | `segmentio/kafka-go.makeLayout` | 786.33MB |
| 8 | `strconv.appendQuotedWith` | 683.09MB |
| 9 | `fmt.Sprint` | 670.45MB |
| 10 | `bytes.growSlice` | 462.68MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 310/312 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/312 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 306/312 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/312 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/312 | `█████░░░░░░░░░░ 35%` |
| 6 | `bytes.growSlice` | 11.91MB | 47/312 | `████░░░░░░░░░░░ 32%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/312 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/312 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/312 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/312 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 112.96GB | 303/312 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/312 | `█████████░░░░░░ 63%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/312 | `█████████░░░░░░ 63%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/312 | `█████████░░░░░░ 62%` |
| 5 | `reflect.unsafe_NewArray` | 48.8GB | 303/312 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.8GB | 288/312 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/312 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/312 | `████░░░░░░░░░░░ 31%` |
| 9 | `reflect.MakeSlice` | 27.36GB | 301/312 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.38GB | 288/312 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
