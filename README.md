## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 436,352 | 🐛 69 | 📅 2026-01-28 [![Build Status](https://github.com/manuzhang/awesome-streaming/workflows/build/badge.svg)](https://github.com/manuzhang/awesome-streaming/actions) ⭐ 2,952 | 🐛 5 | 📅 2026-02-09

A curated list of awesome [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) frameworks, applications, readings and other resources. Inspired by [other awesome projects](https://github.com/sindresorhus/awesome) ⭐ 436,352 | 🐛 69 | 📅 2026-01-28.

## Website

<https://manuzhang.github.io/awesome-streaming/> is a more dynamic website where you can find **updates** of the awesome projects here.

## Table of Contents

* [Streaming Engine](#streaming-engine)
* [Streaming Library](#streaming-library)
* [Streaming Application](#streaming-application)
* [IoT](#iot)
* [DSL](#dsl)
* [Data Pipeline](#data-pipeline)
* [Online Machine Learning](#online-machine-learning)
* [Streaming SQL](#streaming-sql)
* [Toolkit](#toolkit)
* [Benchmark](#benchmark)
* [Closed Source](#closed-source)
* [Readings](#readings)

### Streaming Engine

* [Pathway](https://github.com/pathwaycom/pathway) ⭐ 59,309 | 🐛 30 | 🌐 Python | 📅 2026-02-06 \[Python] - The fastest data processing engine supporting unified workflows for batch, streaming data, and LLM applications.
* [Apache Spark Streaming](https://github.com/apache/spark) ⭐ 42,789 | 🐛 239 | 🌐 Scala | 📅 2026-02-10 \[Scala] - makes it easy to build scalable fault-tolerant streaming applications.
* [Apache Flink](https://github.com/apache/flink) ⭐ 25,773 | 🐛 281 | 🌐 Java | 📅 2026-02-10 \[Java] - system for high-throughput, low-latency data stream processing that supports stateful computation, data-driven windowing semantics and iterative stream processing.
* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 8,778 | 🐛 1,428 | 🌐 Rust | 📅 2026-02-10 \[Rust] - A PostgreSQL-compatible streaming database that is designed to build event-driven applications, real-time ETL pipelines, continuous analytics services, and feature stores for AI applications. It excels in extracting fresh and consistent insights from real-time event streams, database CDC, and time series data within sub-seconds. It unifies streaming and batch processing, enabling users to ingest, join, and analyze both live and historical data at a cloud scale.
* [Faust](https://github.com/robinhood/faust) ⭐ 6,837 | 🐛 276 | 🌐 Python | 📅 2024-07-27 \[Python] - stream processing library, porting the ideas from Kafka Streams to Python
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,671 | 🐛 41 | 🌐 Java | 📅 2026-02-04 \[Clojure/Java] - distributed real-time computation system. Storm is to stream processing what Hadoop is to batch processing.
* [CocoIndex](https://github.com/cocoindex-io/cocoindex) ⭐ 6,061 | 🐛 61 | 🌐 Rust | 📅 2026-02-09 \[Rust/Python] - ETL framework to build fresh index for AI, with realtime incremental updates.
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 4,800 | 🐛 102 | 🌐 Rust | 📅 2026-02-05 \[Rust] - a distributed stream processing engine. Supports SQL and Rust pipelines. Scales up to millions of events per second. Supports stateful operations like windows and joins, state checkpointing for fault-tolerance and recovery of pipelines. Uses the Timely Dataflow model.
* [Apache Heron (incubating)](https://github.com/apache/incubator-heron) ⚠️ Archived \[Java] - a realtime, distributed, fault-tolerant stream processing engine from Twitter.
* [Numaflow](https://github.com/numaproj/numaflow) ⭐ 2,434 | 🐛 255 | 🌐 Rust | 📅 2026-02-10 \[Java/Python/Go/Rust] - Kubernetes native stream processing platform with language agnostic framework. Scalable and cost-efficient
* [Onyx](https://github.com/onyx-platform/onyx) ⚠️ Archived \[Clojure] - Distributed, masterless, high performance, fault tolerant data processing.
* [Apache Ballista](https://github.com/apache/arrow-ballista) ⭐ 1,967 | 🐛 118 | 🌐 Rust | 📅 2026-02-10 \[Rust] - distributed compute platform powered by Apache Arrow.
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 1,952 | 🐛 40 | 🌐 Python | 📅 2025-03-27 \[Python] - data parallel, distributed, stateful stream processing framework.
* [Kuiper](https://github.com/emqx/kuiper) ⭐ 1,677 | 🐛 46 | 🌐 Go | 📅 2026-02-02 \[Golang] - An edge lightweight IoT data analytics/streaming software implemented by Golang, and it can be run at all kinds of resource-constrained edge devices.
* [Wallaroo](https://github.com/WallarooLabs/wallaroo) ⭐ 1,485 | 🐛 346 | 🌐 Pony | 📅 2021-04-06 \[Python] - A fast, stream-processing framework. Wallaroo makes it easy to react to data in real-time. By eliminating infrastructure complexity, going from prototype to production has never been simpler.
* [mantis](https://github.com/Netflix/mantis) ⭐ 1,458 | 🐛 80 | 🌐 Java | 📅 2026-02-03 \[Java] - Netflix's platform to build an ecosystem of realtime stream processing applications
* [Trill](https://github.com/Microsoft/trill) ⭐ 1,267 | 🐛 48 | 🌐 C# | 📅 2024-01-08 \[.NET/C#] - Trill is a high-performance one-pass in-memory streaming analytics engine from Microsoft Research.
* [ArkFlow](https://github.com/arkflow-rs/arkflow) ⭐ 1,248 | 🐛 29 | 🌐 Rust | 📅 2026-02-09 \[Rust] - High-performance Rust stream processing engine, providing powerful data stream processing capabilities, supporting multiple input/output sources and processors.
* [AthenaX](https://github.com/uber/AthenaX) ⚠️ Archived \[Java] - Uber's Stream Analytics Framework used in production
* [Hazelcast Jet](https://github.com/hazelcast/hazelcast-jet) ⚠️ Archived \[Java] - A general purpose distributed data processing engine, built on top of Hazelcast.
* [Apache Samza](https://github.com/apache/samza) ⭐ 837 | 🐛 41 | 🌐 Java | 📅 2025-05-02 \[Scala/Java] - distributed stream processing framework that build on Kafka(messaging, storage) and YARN(fault tolerance, processor isolation, security and resource management).
* [Gearpump](https://github.com/gearpump/gearpump) ⭐ 758 | 🐛 97 | 🌐 Scala | 📅 2022-03-01 \[Scala] - lightweight real-time distributed streaming engine built on Akka.
* [HStreamDB](https://github.com/hstreamdb/hstream) ⭐ 726 | 🐛 11 | 🌐 Haskell | 📅 2024-12-26 \[Haskell] - The streaming database built for IoT data storage and real-time processing.
* [Apache Apex](https://github.com/apache/apex-core) ⚠️ Archived \[Java] - unified platform for big data stream and batch processing.
* [tigon](https://github.com/caskdata/tigon) ⚠️ Archived \[C++/Java] - high throughput real-time streaming processing framework built on Hadoop and HBase.
* [mupd8(muppet)](https://github.com/walmartlabs/mupd8) ⚠️ Archived \[Scala/Java] - mapReduce-style framework for processing fast/streaming data.
* [hailstorm](https://github.com/hailstorm-hs/hailstorm) ⭐ 92 | 🐛 1 | 🌐 Haskell | 📅 2014-06-11 \[Haskell] - distributed stream processing with exactly-once semantics based on Storm.
* [NebulaStream](https://github.com/nebulastream/nebulastream) ⭐ 75 | 🐛 184 | 🌐 C++ | 📅 2026-02-09 \[C++] - High-performance, general-purpose, end-to-end data-management system for cloud-edge-sensor environments.
* [LightSaber](https://github.com/lsds/LightSaber) ⭐ 73 | 🐛 0 | 🌐 C++ | 📅 2021-10-20 \[C++] - Multi-core Window-Based Stream Processing Engine. LightSaber uses code generation for efficient window aggregation.
* [Scramjet Cloud Platform](https://github.com/scramjetorg/transform-hub) ⭐ 69 | 🐛 69 | 🌐 TypeScript | 📅 2025-01-13 \[Python/JavaScript/Node.js] - data processing engine for running multiple data processing apps (sequences) written in Python, JavaScript or TypeScript
* [s4](https://github.com/apache/incubator-s4) ⚠️ Archived \[Java] - general-purpose, distributed, scalable, fault-tolerant, pluggable platform that allows programmers to easily develop applications for processing continuous unbounded streams of data.
* [Maki Nage](https://github.com/maki-nage/makinage) ⭐ 42 | 🐛 8 | 🌐 Python | 📅 2022-04-24 \[Python] - A stream processing framework for data scientists, based on Kafka and ReactiveX.
* [SABER](https://github.com/lsds/Saber) ⭐ 42 | 🐛 10 | 🌐 Java | 📅 2022-11-16 \[Java/C] - Window-Based Hybrid CPU/GPU Stream Processing Engine.
* [SPQR](https://github.com/ottogroup/SPQR) ⚠️ Archived \[Java] - dynamic framework for processing high volumn data streams through pipelines.
* [Teknek](https://github.com/edwardcapriolo/teknek-core) ⭐ 9 | 🐛 1 | 🌐 Java | 📅 2015-12-15 \[Java] - Simple elegant stream processing with interactive prototying shell SOL (Stream Operator Language)
  Mesos, designed for high performance data processing jobs that require flexibility & control.
* [WindFlow](https://paragroup.github.io/WindFlow) \[C++] - A C++17 Data Stream Processing Parallel Library for Multicores and GPUs.

### Streaming Library

* [Mediapipe](https://github.com/google/mediapipe) ⭐ 33,714 | 🐛 604 | 🌐 C++ | 📅 2026-02-04 - Cross-platform, customizable ML solutions for live and streaming media.
* [Apache Kafka Streams](https://github.com/apache/kafka) ⭐ 31,864 | 🐛 269 | 🌐 Java | 📅 2026-02-10 \[Java] - lightweight stream processing library included in Apache Kafka (since 0.10 version).
* [Akka Streams](https://github.com/akka/akka) ⭐ 13,262 | 🐛 900 | 🌐 Scala | 📅 2026-02-09 \[Scala] - stream processing library on Akka Actors.
* [Benthos](https://github.com/Jeffail/benthos) ⭐ 8,582 | 🐛 552 | 🌐 Go | 📅 2026-02-09 \[Go] - Benthos is a high performance and resilient message streaming service, able to connect various sources and sinks and perform arbitrary actions, transformations and filters on payloads
* [FastStream](https://github.com/airtai/faststream) ⭐ 4,949 | 🐛 117 | 🌐 Python | 📅 2026-02-09 \[Python] - powerful and easy-to-use Python library simplifying the process of writing producers and consumers for message queues, handling all the parsing, networking and documentation generation automatically. Supports multiple protocols such as Apache Kafka, RabbitMQ and alike.
* [StreamAlert](https://github.com/airbnb/streamalert) ⭐ 2,887 | 🐛 90 | 🌐 Python | 📅 2023-10-23 \[Python] - Airbnb's Real-time Data Analysis and Alerting.
* [FS2(prev. 'Scalaz-Stream')](https://github.com/functional-streams-for-scala/fs2) ⭐ 2,441 | 🐛 130 | 🌐 Scala | 📅 2026-02-04 \[Scala] - Compositional, streaming I/O library for Scala.
* [monix](https://github.com/monix/monix) ⭐ 1,937 | 🐛 114 | 🌐 Scala | 📅 2026-01-27 \[Scala] - high-performance Scala / Scala.js library for composing asynchronous and event-based programs.
* [YoMo](https://github.com/yomorun/yomo) ⭐ 1,882 | 🐛 3 | 🌐 Go | 📅 2026-02-03 \[Go] - An open source Streaming Serverless Framework for building Low-latency Geo-distributed system. YoMo Built atop [QUIC Transport Protocol](https://en.wikipedia.org/wiki/QUIC) and Functional Reactive Programming interface.
* [Quix Streams](https://github.com/quixio/quix-streams) ⭐ 1,520 | 🐛 23 | 🌐 Python | 📅 2026-02-02 \[Python] - a streaming library originally designed for the McLaren Formula 1 racing team that can process high volumes of time-series data with up to nanosecond precision using Apache Kafka as a message broker.
* [Streamz](https://github.com/python-streamz/streamz) ⭐ 1,292 | 🐛 120 | 🌐 Python | 📅 2026-02-05 \[Python] - A lightweight library for building pipelines to manage continuous streams of data; supports complex pipelines that involve branching, joining, flow control, feedback, back pressure, and so on.
* [Streamiz](https://github.com/LGouellec/kafka-streams-dotnet) ⭐ 525 | 🐛 25 | 🌐 C# | 📅 2026-01-26 \[C#] - a .Net Stream Processing Library for Apache Kafka
* [Tributary](https://github.com/timkpaine/tributary) ⭐ 459 | 🐛 10 | 🌐 Python | 📅 2025-12-20 \[Python] - A python library for constructing dataflow graphs. Supports synchronous, reactive data streams built using python generators that mimic complex event processors, as well as lazily-evaluated acyclic graphs and functional currying streams.
* [Substation](https://github.com/brexhq/substation) ⭐ 390 | 🐛 1 | 🌐 Go | 📅 2026-01-20 \[Go] - Substation is a cloud native data pipeline and transformation toolkit written in Go.
* [Swave](https://github.com/sirthias/swave) ⭐ 173 | 🐛 8 | 🌐 Scala | 📅 2018-06-18 \[Scala] - A lightweight Reactive Streams Infrastructure Toolkit for Scala.
* [Streamline](https://github.com/hortonworks/streamline) ⭐ 167 | 🐛 123 | 🌐 Java | 📅 2023-08-27 \[Java] - Stream Analytics Framework by Hortonworks, designed as a wrapper around existing streaming solutions like Storm. Aimed to allow users to drag-and-drop streaming components to focus on business logic.
* [Daggy](https://github.com/synacker/daggy) ⭐ 158 | 🐛 8 | 🌐 C++ | 📅 2025-11-03 \[C++] - real-time streams aggregation and catching.
* [Stream Ops](https://github.com/nanosai/stream-ops-java) ⭐ 49 | 🐛 4 | 🌐 Java | 📅 2019-10-20 \[Java] - A fully embeddable data streaming engine and stream processing API for Java.
* [Scramjet Node.js](https://github.com/scramjetorg/framework-js) ⭐ 39 | 🐛 10 | 🌐 TypeScript | 📅 2022-04-29 - \[Node.js] functional reactive stream programming framework written on top of Node.js object streams + [the legacy Scramjet.js version](https://github.com/scramjetorg/scramjet) ⭐ 253 | 🐛 3 | 📅 2022-12-26
* [Scramjet Python](https://github.com/scramjetorg/framework-python) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2023-10-24 - \[Python] functional reactive stream programming framework written from scratch operating on object, string and buffer streams.
* [Scramjet C++](https://github.com/scramjetorg/framework-cpp) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2022-09-09 - \[C++] functional reactive stream programming framework written on top of Node.js object streams.

### Streaming Application

* [storm-crawler](https://github.com/DigitalPebble/storm-crawler) ⭐ 961 | 🐛 29 | 🌐 Java | 📅 2026-02-09 \[Java] - Web crawler SDK based on Apache Storm.
* [Zilla](https://github.com/aklivity/zilla) ⭐ 676 | 🐛 171 | 🌐 Java | 📅 2026-02-09 \[Java] - Cross-platform, API gateway built for event-driven architectures and streaming that supports standard protocols such as HTTP, SSE, gRPC, MQTT and the native Kafka protocol.
* [straw](https://github.com/rwalk/straw) ⭐ 102 | 🐛 2 | 🌐 Python | 📅 2016-03-09 \[Python/Java] - A platform for real-time streaming search.
* [javactrl-kafka](https://github.com/javactrl/javactrl-kafka) ⭐ 15 | 🐛 5 | 🌐 Java | 📅 2025-04-30 \[Java] - An application of a stateful stream processing for workflow as Java code (microservices orchestration, business process automation, and more).

### IoT

* [Apache StreamPipes](https://github.com/apache/incubator-streampipes) ⭐ 704 | 🐛 143 | 🌐 Java | 📅 2026-02-09 \[Java] - a self-service (Industrial) IoT toolbox to enable non-technical users to connect, analyze and explore IoT data streams.
* [sensorbee](https://github.com/sensorbee/sensorbee) ⭐ 230 | 🐛 39 | 🌐 Go | 📅 2019-11-04 \[Go] - lightweight stream processing engine for IoT.
* [Apache Edgent](https://github.com/apache/incubator-edgent) ⚠️ Archived \[Java] - a programming model and runtime that enables continuous streaming analytics on gateways and edge devices which can work with centralized systems to provide efficient and timely analytics across the whole IoT ecosystem: from the center to the edge, opens sourced by IBM.

### DSL

* [Apache Beam](https://github.com/apache/beam) ⭐ 8,481 | 🐛 4,160 | 🌐 Java | 📅 2026-02-10 \[Java, Python, SQL, Scala, Go] - unified model and set of language-specific SDKs for defining and executing data processing workflows, and also data ingestion and integration flows, supporting Enterprise Integration Patterns (EIPs) and Domain Specific Languages (DSLs), open sourced by Google.
* [summingbird](https://github.com/twitter/summingbird) ⚠️ Archived \[Scala] - library that lets you write MapReduce programs that look like native Scala or Java collection transformations and execute them on a number of well-known distributed MapReduce platforms, including Storm and Scalding.
* [Streamparse](https://github.com/Parsely/streamparse) ⭐ 1,506 | 🐛 60 | 🌐 Python | 📅 2025-07-22 \[Python] - lets you run Python code against real-time streams of data via Apache Storm.
* [Esper](https://github.com/espertechinc/esper) ⭐ 874 | 🐛 16 | 🌐 Java | 📅 2024-04-26 \[Java] - component for complex event processing (CEP) and event series analysis.
* [coast](https://github.com/bkirwi/coast) ⭐ 60 | 🐛 5 | 🌐 Scala | 📅 2016-08-27 \[Scala] - a DSL that builds DAGs on top of Samza and provides exactly-once semantics.

### Data Pipeline

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 31,864 | 🐛 269 | 🌐 Java | 📅 2026-02-10 \[Scala/Java] - distributed, partitioned, replicated commit log service, which provides the functionality of a messaging system, but with a unique design.
* [nsq](https://github.com/nsqio/nsq) ⭐ 25,926 | 🐛 73 | 🌐 Go | 📅 2025-07-13 \[Go] - realtime distributed messaging platform designed to operate at scale, handling billions of messages per day.
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,333 | 🐛 278 | 🌐 Java | 📅 2026-02-09 \[Java] - distributed messaging and streaming platform with low latency, high performance and reliability, trillion-level capacity and flexible scalability.
* [Apache Pulsar](https://github.com/apache/incubator-pulsar) ⭐ 15,082 | 🐛 1,638 | 🌐 Java | 📅 2026-02-09 \[Java] - distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 11,699 | 🐛 657 | 🌐 C++ | 📅 2026-02-10 \[C++] - Redpanda is Kafka compatible, ZooKeeper-free, JVM-free and source available.
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 9,481 | 🐛 85 | 🌐 Java | 📅 2026-02-10 \[Scala/Java] - cloud-first alternative to Kafka by decoupling durability to S3 and EBS. 100% Kafka compatible. 10x cost-effective. Autoscale in seconds. Single-digit ms latency.
* [fluvio](https://github.com/infinyon/fluvio) ⭐ 5,162 | 🐛 137 | 🌐 Rust | 📅 2026-02-10 \[Rust/WASM] - Real-time programmable data streaming platform with in-line computation capabilities.
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,354 | 🐛 31 | 🌐 Go | 📅 2026-02-09 \[Go] - an open source customer data infrastructure (segment, mparticle alternative).
* [databus](https://github.com/linkedin/databus) ⭐ 3,679 | 🐛 40 | 🌐 Java | 📅 2023-09-28 \[Java] - Linkedin's source-agnostic distributed change data capture system.
* [ingestr](https://github.com/bruin-data/ingestr) ⭐ 3,382 | 🐛 17 | 🌐 Python | 📅 2026-02-09 \[Python] - CLI tool to copy data between any source and destination with a single command. Supports 50+ connectors including databases, SaaS apps, and data warehouses.
* [flume](https://github.com/apache/flume) ⭐ 2,558 | 🐛 91 | 🌐 Java | 📅 2024-10-10 \[Java] - distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data.
* [NATS streaming](https://github.com/nats-io/nats-streaming-server) ⚠️ Archived \[Go] - fast disk-backed messaging solution
* [Bruin](https://github.com/bruin-data/bruin) ⭐ 1,363 | 🐛 40 | 🌐 Go | 📅 2026-02-09 \[Go] - End-to-end data pipeline tool combining ingestion from 50+ sources, SQL/Python transformations, and built-in data quality checks in a single CLI.
* [metaq](https://github.com/killme2008/Metamorphosis) ⭐ 1,332 | 🐛 49 | 🌐 Java | 📅 2020-04-07 \[Java] - Taobao's high available, high performance distributed messaging system
* [brooklin](https://github.com/linkedin/Brooklin/) ⭐ 952 | 🐛 34 | 🌐 Java | 📅 2026-02-04 \[Java] - a distributed system intended for streaming data between various heterogeneous source and destination systems with high reliability and throughput at scale from Linkedin (replaced databus).
* [camus](https://github.com/linkedin/camus) ⚠️ Archived \[Java] - Linkedin's Kafka -> HDFS pipeline.
* [suro](https://github.com/Netflix/suro) ⚠️ Archived \[Java] - data pipeline service for collecting, aggregating, and dispatching large volume of application events including log data.
* [Gazette](https://github.com/gazette/core) ⭐ 784 | 🐛 24 | 🌐 Go | 📅 2026-02-09 \[golang] - Distributed streaming infrastructure built on cloud storage which makes it easy to mix and match batch and streaming paradigms.
* [LogDevice](https://logdevice.io/) \[C++] - a high-performant distributed system by Facebook for streaming and storing sequential data, using a log structure.

### Online Machine Learning

* [River](https://github.com/online-ml/river) ⭐ 5,704 | 🐛 116 | 🌐 Python | 📅 2026-02-09 \[Python] - online machine learning library.
* [DataSketches](https://github.com/DataSketches/sketches-core) ⭐ 945 | 🐛 7 | 🌐 Java | 📅 2026-02-07 \[Java] - sketches library from Yahoo!.
* [streamDM](https://github.com/huawei-noah/streamDM) ⭐ 500 | 🐛 4 | 🌐 Scala | 📅 2023-04-16 \[Scala] - mining Big Data streams using Spark Streaming from Huawei.
* [trident-ml](https://github.com/pmerienne/trident-ml) ⭐ 384 | 🐛 3 | 🌐 Java | 📅 2023-12-16 \[Java] - realtime online machine learning library based on Trident.
* [Apache Samoa](https://github.com/apache/incubator-samoa) ⭐ 250 | 🐛 16 | 🌐 Java | 📅 2023-04-16 \[Java] - distributed streaming machine learning (ML) framework that contains a programing abstraction for distributed streaming ML algorithms.
* \[Numalogic] (<https://github.com/numaproj/numalogic> ⭐ 174 | 🐛 52 | 🌐 Python | 📅 2024-10-15) \[Python] - Collection of ML models and libraries for real-time anomaly detection and forecasting on time series data. Built on Numaflow, a K8s native stream processing platform
* [StormCV](https://github.com/sensorstorm/StormCV) ⭐ 172 | 🐛 3 | 🌐 Java | 📅 2016-12-20 \[Java] - enables the use of Apache Storm for video processing by adding computer vision (CV) specific operations and data model.
* [yurita](https://github.com/paypal/yurita) ⚠️ Archived \[Scala] - Anomaly detection framework built on Spark Structured Streaming from Paypal.
* [StreamingBandit](https://github.com/Nth-iteration-labs/streamingbandit) ⭐ 83 | 🐛 4 | 🌐 Python | 📅 2025-09-04 \[Python] - Provides a webserver to quickly setup and evaluate possible solutions to contextual multi-armed bandit (cMAB) problems.

### Streaming SQL

* [pipelinedb](https://github.com/pipelinedb/pipelinedb) ⭐ 2,655 | 🐛 133 | 🌐 C | 📅 2022-02-20 \[C] - An open-source relational database that runs SQL queries continuously on streams, incrementally storing results in tables.
* [Proton](https://github.com/timeplus-io/proton) ⭐ 2,133 | 🐛 89 | 🌐 C++ | 📅 2026-02-09 \[C++] - A unified streaming and historical data analytics database in a single binary, powered by ClickHouse.
* [Siddhi](https://github.com/siddhi-io/siddhi) ⭐ 1,577 | 🐛 124 | 🌐 Java | 📅 2025-08-08 \[Java] - A cloud native Streaming and Complex Event Processing engine that understands Streaming SQL queries in order to capture events from diverse data sources, process them, detect complex conditions, and publish output to various endpoints in real time.
* [ksqlDB](https://github.com/confluentinc/ksql) ⭐ 287 | 🐛 1,312 | 🌐 Java | 📅 2026-02-10 \[Java] - A cloud-native, source-available [database](https://ksqldb.io/) purpose-built for stream processing applications
* [squall](https://github.com/epfldata/squall) ⭐ 273 | 🐛 3 | 🌐 Java | 📅 2017-05-18 \[Java] - Squall executes SQL queries on top of Storm for doing online processing.
* [StreamCQL](https://github.com/Zhiqiang-He/StreamCQL) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2017-07-12 \[Java] - Continuous Query Language on RealTime Computation System.
* [Materialize](https://materialize.com) \[Rust] - A source-available streaming SQL engine for maintaining materialized views on data from message brokers and databases.

### Benchmark

* [streaming-benchmarks](https://github.com/yahoo/streaming-benchmarks) ⭐ 647 | 🐛 25 | 🌐 Jupyter Notebook | 📅 2023-12-17 \[Java] - Benchmarks for Low Latency (Streaming) solutions including Apache Storm, Apache Spark, Apache Flink, etc.
* [flotilla](https://github.com/tylertreat/Flotilla) ⚠️ Archived \[Go] - Automated message queue orchestration for scaled-up benchmarking.
* [storm-perf-test](https://github.com/yahoo/storm-perf-test) ⭐ 74 | 🐛 2 | 🌐 Java | 📅 2023-03-21 \[Java] - a simple storm performance/stress test.

### Toolkit

* [akka](https://github.com/akka/akka) ⭐ 13,262 | 🐛 900 | 🌐 Scala | 📅 2026-02-09 \[Scala] - toolkit and runtime for building highly concurrent, distributed, and resilient message-driven application on the JVM.
* [aeron](https://github.com/real-logic/Aeron) ⭐ 8,441 | 🐛 16 | 🌐 Java | 📅 2026-02-07 \[Java/C++] - efficient reliable unicast and multicast message transport.
* [pulsar](https://github.com/quantmind/pulsar/) ⚠️ Archived \[Python] - Actor based event driven concurrent framework for Python.
* [Apache Pekko](https://github.com/apache/incubator-pekko) ⭐ 1,526 | 🐛 201 | 🌐 Scala | 📅 2026-02-09 \[Scala, Java] - Fork of Akka 2.6.x, prior to the Akka project's adoption of the Business Source License.
* [Turbine](https://github.com/Netflix/Turbine) ⚠️ Archived \[Java] - tool for aggregating streams of Server-Sent Event (SSE) JSON data into a single stream.
* [Nussknacker](https://github.com/TouK/nussknacker) ⭐ 708 | 🐛 66 | 🌐 Scala | 📅 2026-02-09 \[Scala] - A visual tool to define and run real-time decision algorithms.
* [StreamFlow](https://github.com/lmco/streamflow) ⭐ 255 | 🐛 35 | 🌐 Java | 📅 2024-12-16 \[Java] - stream processing tool designed to help build and monitor processing workflows.
* [samza-luwak](https://github.com/romseygeek/samza-luwak) ⭐ 100 | 🐛 0 | 🌐 Java | 📅 2014-11-10 \[Java] - uses Luwak, a stored-query engine built on Lucene, to implement full-text search on streams.
* [Streamdal](https://streamdal.com) \[Go/Node.js/Python] - A tool to embed privacy controls in your application code to detect PII as it enters and leaves your systems, preventing it from reaching unintended data streams or pipelines.

### Closed Source

* [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/) \[Java] - real-time, fully managed and scalable data stream engine provided by AWS.
* [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) \[.NET] a massively scalable, fully managed, real-time, data stream engine provided by Microsoft Azure.
* [Cloud Dataflow](https://cloud.google.com/dataflow/)\[Java, Python, SQL, Scala] - Google's managed stream and batch data processing engine. Supports running Beam pipelines.
* [concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) \[C++] - a distributed stream processing framework built in C++ on top of Apache.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/) \[Python/Java/Scala] - platform for distributed processing and real-time analytics. Provides toolkits for advanced analytics like geospatial, time series, etc. out of the box.
* [jubatus](http://jubat.us/en/) \[C++] - distributed processing framework and streaming machine learning library.
* [millwheel](http://research.google.com/pubs/pub41378.html) - framework for building low-latency data-processing applications that is widely used at Google.
* [NVIDIA Deep Stream](https://developer.nvidia.com/deepstream-sdk) \[Python/C/C++] - a platform for real-time image, video and audio processing, preferably using on edge devices or cloud.

### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) by Tyler Akidau.
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](https://arxiv.org/abs/1708.02621)
4. [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) by Josh Fischer & Ning Wang
5. [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) by Reuven Lax, Slava Chernyak, and Tyler Akidau
6. [Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow) by Bas P. Harenslak and Julian Rutger de Ruiter

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)

Licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
