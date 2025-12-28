# 👨🏻‍💻 Marcelo Tesla

[![GitHub followers](https://img.shields.io/github/followers/M-Tesla?label=Follow&style=social)](https://github.com/M-Tesla/?tab=follow)
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/marcelo-tesla/)](https://www.linkedin.com/in/marcelo-tesla/)
[![ProfileViews](https://komarev.com/ghpvc/?username=M-Tesla&color=00FFFF&style=flat)](https://komarev.com/ghpvc/?username=M-Tesla)

Database & Systems Engineer specializing in low-level systems programming with focus on performance-critical applications. I build high-performance data tools, database engines, network services, and system utilities from scratch using Zig, Rust, and Go. My work emphasizes zero-GC architectures, memory safety, and ultra-low latency designs that achieve orders of magnitude improvements over traditional solutions.

Currently building **Glacier** - a pure Zig OLAP query engine that processes Apache Iceberg tables and Parquet files with ~8 MB binary size, 5-50 ms cold start, and zero garbage collection pauses.

<!-- START OF PROFILE STACK, DO NOT REMOVE -->
| 💻 **Technology** | 🚀 **Projects** |
| - | - |
| [![Zig](https://img.shields.io/static/v1?label=&message=Zig&color=F7A41D&logo=Zig&logoColor=FFFFFF)](https://ziglang.org/) | [![Glacier](https://img.shields.io/static/v1?label=&message=Glacier&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/M-Tesla/Glacier) |
| [![Rust](https://img.shields.io/static/v1?label=&message=Rust&color=000000&logo=Rust&logoColor=FFFFFF)](https://www.rust-lang.org/) | Coming soon... |
| [![Go](https://img.shields.io/static/v1?label=&message=Go&color=00ADD8&logo=Go&logoColor=FFFFFF)](https://go.dev/) | Coming soon... |
| [![Python](https://img.shields.io/static/v1?label=&message=Python&color=3776AB&logo=Python&logoColor=FFFFFF)](https://www.python.org/) | Coming soon... |
<!-- END OF PROFILE STACK, DO NOT REMOVE -->

## 🎯 Core Expertise

**OLAP & OLTP Database Systems**
- SQL query engines: parser design, optimizer, execution planner, expression evaluation
- Aggregate and window functions with multi-dimensional grouping (ROLLUP, CUBE, GROUPING SETS)
- Query optimization: predicate pushdown, column/file pruning, join reordering, cost-based optimization
- Indexing structures: B-Tree, B+Tree, B*Tree, Hash indexes, Bitmap indexes
- Storage internals: Write-Ahead Logging (WAL), Log-Structured Merge Trees (LSM-Tree), buffer pool management
- MOLAP storage engines with dimensional hierarchies and cube materialization
- ROLAP systems and data warehousing schemas (Star, Snowflake, Galaxy)
- Transaction management: MVCC, isolation levels, distributed transactions, two-phase commit

**Low-Level Systems Programming**
- Memory management: custom allocators, arena allocation, memory pools, zero-copy architectures
- Concurrency primitives: lock-free data structures, atomic operations, thread synchronization
- Performance optimization: SIMD vectorization, cache-friendly algorithms, CPU profiling
- Network programming: TCP/IP socket handling, HTTP/HTTPS clients, protocol implementation
- Compression algorithms: Snappy, LZ4, Zstd, dictionary encoding, run-length encoding
- Binary protocols: Thrift, Protocol Buffers, Apache Arrow, custom wire formats
- File I/O optimization: mmap, async I/O, direct I/O, buffered streaming

**Modernization & Performance Engineering**
- Legacy system rewrites: migrating monolithic JVM applications to lightweight native binaries
- Cost reduction: 10x-100x reduction in cloud compute costs through efficient resource utilization
- Latency optimization: sub-millisecond query response times, eliminating GC pauses
- Memory footprint reduction: from GB-scale heap usage to MB-scale deterministic allocation
- Cold start elimination: millisecond startup times vs multi-second JVM initialization
- Deployment simplification: single static binary vs complex dependency management (JARs, runtimes)
- Horizontal scalability: stateless architectures, shared-nothing designs, data partitioning strategies

## 💡 Development Philosophy

**Zero Hard-Coding** - Everything generic and dynamic. No schemas baked into code. Runtime type resolution for all data formats.

**Memory Safety** - No leaks, no undefined behavior. GPA-verified allocations. Arena-based management with deterministic cleanup.

**Performance First** - Ultra-low latency targets. Minimal memory footprint. Zero garbage collection. Built for production workloads.

---

<div align="center">

**Building the future of data processing, one Zig line at a time.**

[![GitHub](https://img.shields.io/badge/GitHub-M-Tesla-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/M-Tesla)
[![Codeberg](https://img.shields.io/badge/Codeberg-M__Tesla-2185D0?style=for-the-badge&logo=codeberg&logoColor=white)](https://codeberg.org/M_Tesla)

</div>
