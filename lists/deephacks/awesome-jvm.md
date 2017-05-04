<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="https://github.com/deephacks/awesome-jvm">https://github.com/deephacks/awesome-jvm</a> with ranks
</p>
---
# Awesome JVM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)

A curated list of awesome JVM low level and performance related stuff.

- [Awesome JVM](#awesome-jvm)
    - [Bytecode](#bytecode)
    - [Garbage collectors](#garbage-collectors)
    - [Load tools](#load-tools)
    - [Languages](#languages)
    - [Memory and Concurrency](#memory-and-concurrency)
    - [Metaprogramming](#metaprogramming)
    - [Native](#native)
    - [Network](#network)
    - [Nix tools](#nix-tools)
    - [Profilers](#profilers)
    - [Runtimes](#runtimes)
    - [Virtual Machines](#virtual-machines)
- [Resources](#resources)
    - [Communities](#communities)    
    - [Documentation](#documentation)
    - [Media](#media)
    - [People](#people)
- [Contributing](#contributing)


## Bytecode

*Tools for bytecode manipulation and analysis.*

* [asmtools](https://wiki.openjdk.java.net/display/CodeTools/asmtools) - Used to develop tools for the production of Java .class files.
* [Byte Buddy](http://bytebuddy.net) - Code generation library creating Java classes at runtime without the help of a compiler.
* [Jitescript ★139](https://github.com/qmx/jitescript) - Bytecode generation library similar to BiteScript. 

## Garbage collectors

*Garbage collectors for the JVM.*

* [Azul Pauseless Garbage Collection](http://www.azulsystems.com/sites/default/files//images/wp_pgc_zing_v5.pdf) - Providing continuous, pauseless operation for Java applications.
* [Balanced GC](http://www.ibm.com/developerworks/websphere/techjournal/1108_sciampacone/1108_sciampacone.html) - GC policy available in the Java Virtual Machine for IBM WebSphere Application Server V8.
* [Epsilon GC](http://openjdk.java.net/jeps/8174901) - Completely passive GC implementation with bounded allocation limit, and lowest runtime performance overhead possible.
* [G1](http://www.oracle.com/technetwork/java/javase/tech/g1-intro-jsp-135488.html) - The Garbage-First Garbage Collector.
* [Shenandoah](http://openjdk.java.net/jeps/189) - Ultra-Low-Pause-Time Garbage Collector.
* [The Garbage Collection Handbook](http://gchandbook.org) - Book that addresses new challenges to garbage collection made by recent advances in hardware and software.

## Load tools

*Tools that generate load and measure the system accurately without coordinated omission*

* [Gatling](http://gatling.io) - Asynchronous non-blocking scenario driven load testing tool for testing HTTP servers.
* [wrk2 ★937](https://github.com/giltene/wrk2) - A constant throughput, correct latency recording variant of wrk.

## Languages

*Languages running on the JVM.*
* [Ceylon](http://ceylon-lang.org/) - Object-oriented, strong and static programming language with an emphasis on immutability, created by Red Hat.
* [Clojure](http://clojure.org/) - Dialect of Lisp created by Rich Hickey. Dynamically typed with emphasis on functional programming.
* [Erjang](http://www.erjang.org) - A JVM-based Erlang VM.
* [Eta](http://eta-lang.org/) - Pure, lazy, strongly typed functional programming language on the JVM.
* [Frege ★2744](https://github.com/Frege/frege) - Pure functional programming language in the spirit of Haskell.
* [gojava ★141](https://github.com/sridharv/gojava) - Java bindings for Go packages.
* [Golo](http://golo-lang.org/) - A simple dynamic language that makes extensive usage of `invokedynamic`.
* [Groovy](http://www.groovy-lang.org/) - Optionally typed and dynamic language, with static-typing and static compilation capabilities.
* [Java](http://www.oracle.com/technetwork/java/javase/overview/index.html) - General-purpose, concurrent, strongly typed, class-based object-oriented language.
* [JRuby](http://jruby.org) - Implementation of the Ruby language on the JVM.
* [JPHP](http://j-php.net) - PHP on the Java VM.
* [Jython](http://www.jython.org) - Python for the Java Platform.
* [Kawa](http://www.gnu.org/software/kawa/) - Extension of the Scheme language, which is in the Lisp family of programming languages.
* [Kotlin](http://kotlinlang.org/) - Statically typed programming language for the JVM, Android and the browser.
* [LuaJ](http://www.luaj.org/luaj/3.0/README.html) - Java-centric implementation of lua vm built to leverage standard Java features.
* [Nashorn](http://openjdk.java.net/projects/nashorn/) - Lightweight high-performance JavaScript runtime in Java with a native JVM.
* [Nodyn](http://nodyn.io/) - Node.js compatible framework, running on the JVM powered by the DynJS Javascript runtime.
* [OCaml-Java](http://www.ocamljava.org/) - Supports OCaml language v4. Generates plain Java bytecode and have seamless integration with Java.
* [Rembulan ★78](https://github.com/mjanicek/rembulan) - Rembulan is an implementation of Lua 5.3 for the JVM, written in pure Java with minimal dependencies.
* [Renjin](http://www.renjin.org/) - JVM-based interpreter for the R language for the statistical analysis
* [Scala](http://www.scala-lang.org/) - Strong and static programming language that combine object-oriented and functional programming ideas.
* [Xtend](http://www.eclipse.org/xtend/) - Flexible and expressive dialect of Java, which compiles into Java 5 source code.

## Memory and concurrency

*Tools and data structures for efficient memory layout and concurrent access.*

* [Agera ★6440](https://github.com/google/agera) - Reactive Programming for Android by Google.
* [Agrona ★783](https://github.com/real-logic/Agrona) - Library of data structures and utility methods that are a common need when building high-performance applications.
* [Apache Arrow](http://arrow.apache.org/) - A high-performance cross-system data layer for columnar in-memory analytics.
* [bloofi ★51 ⏳1Y](https://github.com/lemire/bloofi) - Java implementation of multidimensional Bloom filters
* [Cap’n Proto](https://capnproto.org/) - Insanely fast data interchange format and capability-based RPC system.
* [caffeine ★2464](https://github.com/ben-manes/caffeine) - A high performance caching library for Java 8.
* [Chronicle-Bytes ★70](https://github.com/OpenHFT/Chronicle-Bytes) - Low level memory access wrappers.
* [Chronicle-Queue ★1072](https://github.com/OpenHFT/Chronicle-Queue) - Micro second messaging that stores everything to disk.
* [Chronicle-Map ★954](https://github.com/OpenHFT/Chronicle-Map) - In-memory key-value store designed for low-latency and/or multi-process applications.
* [clj-ds ★208 ⏳3Y](https://github.com/krukow/clj-ds) - Clojure's data structures modified for use outside of Clojure.
* [colfer ★214](https://github.com/pascaldekloe/colfer) - Binary serialization format and class generator.
* [commons-math](http://commons.apache.org/proper/commons-math) - Library of lightweight, self-contained mathematics and statistics components.
* [CuckooFilter4J ★33](https://github.com/MGunlogson/CuckooFilter4J) - Bloom filter replacement for approximated set-membership queries.
* [cyclops ★348](https://github.com/aol/cyclops) - Integration modules for RxJava, Reactor, FunctionalJava, Guava & Javaslang.
* [java-concurrent-hash-trie-map ★100](https://github.com/romix/java-concurrent-hash-trie-map) - Java port of a concurrent trie hash map implementation from Scala collections.
* [java-hll ★178](https://github.com/aggregateknowledge/java-hll) - Java library for the HyperLogLog algorithm.
* [JavaFastPFOR ★256](https://github.com/lemire/JavaFastPFOR) - Library to compress and uncompress arrays of integers very fast.
* [fasttuple ★125](https://github.com/boundary/fasttuple) - Collections that are laid out adjacently in both on- and off-heap memory.
* [FlatBuffers](http://google.github.io/flatbuffers/) - Efficient cross platform serialization library for C++, C#, Go, Java, JavaScript, PHP, and Python.
* [geohash ★183](https://github.com/davidmoten/geo) - Java utility methods for geohashing.
* [gs-collections ★1654 ⏳1Y](https://github.com/goldmansachs/gs-collections) - Goldman Sachs collections framework.
* [hollow ★451](https://github.com/Netflix/hollow) - Java library and comprehensive toolset for harnessing small to moderately sized in-memory datasets.
* [high-scale-lib ★279 ⏳2Y](https://github.com/boundary/high-scale-lib) - Cliff Click's High Scale Library.
* [hppc ★373](https://github.com/carrotsearch/hppc) - High Performance Primitive Collections.
* [injector ★53 ⏳2Y](https://github.com/belliottsmith/injector) -  A new Executor for Java.
* [javaslang](http://www.javaslang.io/) - Functional Library for Java 8+.
* [JCTools](http://jctools.github.io/JCTools/) - Concurrent data structures currently missing from the JDK.
* [Koloboke](https://github.com/OpenHFT/Koloboke) - Java Collections til the last breadcrumb of memory and performance.
* [LevelDB](https://github.com/dain/leveldb) - Rewrite (port) of LevelDB in Java.
* [lightweight_trie](https://github.com/bryanduxbury/lightweight_trie) - A very memory-efficient trie (radix tree) implementation.
* [lmdbjni](https://github.com/deephacks/lmdbjni) - Java API to LMDB (HawtJNI) which is an ultra-fast, ultra-compact key-value embedded data store written in C.
* [lmdbjava](https://github.com/lmdbjava/lmdbjava) - Java API to LMDB (JNR) which is an ultra-fast, ultra-compact key-value embedded data store written in C.
* [low-gc-membuffers ★118 ⏳2Y](https://github.com/cowtowncoder/low-gc-membuffers) - In-memory circular buffers that use direct ByteBuffers to minimize GC overhead.
* [lwjgl3](https://github.com/LWJGL/lwjgl3) - Java library that enables cross-platform access to popular native APIs useful in the development of graphics (OpenGL), audio (OpenAL) and parallel computing (OpenCL) applications.
* [MapDB](http://www.mapdb.org) - Collections backed by off-heap or on-disk storage.
* [netty-buffers](http://netty.io/wiki/using-as-a-generic-library.html#wiki-h2-1) - Memory buffer pool implementation similar to jemalloc.
* [ObjectLayout](http://objectlayout.org) - A layout-optimized Java data structure package.
* [ohc ★175](https://github.com/snazy/ohc) - Java large off heap cache developed for Apache Cassandra 3.0.
* [okio ★3733](https://github.com/square/okio) - Modern Java IO library that do clever things to save CPU and memory.
* [one-nio ★188 ⏳1Y](https://github.com/odnoklassniki/one-nio) - library for building high performance Java servers.
* [parquet](https://parquet.apache.org/) - Columnar storage format that uses the record shredding and assembly algorithm described in the Dremel paper.
* [PauselessHashMap ★124 ⏳2Y](https://github.com/giltene/PauselessHashMap) - A java.util.HashMap compatible map that won't stall puts or gets when resizing.
* [pcollections ★359](https://github.com/hrldcpr/pcollections) - A Persistent Java Collections Library.
* [protobuf](https://developers.google.com/protocol-buffers) - Google's data interchange format.
* [Quasar](http://www.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.
* [rtree ★485](https://github.com/davidmoten/rtree) - Immutable in-memory R-tree and R*-tree implementations in Java with reactive api.
* [Reactive Streams](http://www.reactive-streams.org/) - Standard for asynchronous stream processing with non-blocking back pressure.
* [RoaringBitmap ★536](https://github.com/RoaringBitmap/RoaringBitmap) - A better compressed bitset in Java.
* [rollinghashjava ★38 ⏳1Y](https://github.com/lemire/rollinghashjava) - Rolling hash functions in Java.
* [Reactor](http://projectreactor.io/) - Reactive data applications on the JVM for Java, Groovy, Clojure and other.
* [RxJava ★23780](https://github.com/ReactiveX/RxJava) - Library for composing asynchronous and event-based programs using observable sequences.
* [SmoothieMap ★114 ⏳1Y](https://github.com/OpenHFT/SmoothieMap) - java.util.Map impl with worst put latencies more than 100 times smaller than java.util.HashMap.
* [Simple Binary Encoding ★1078](https://github.com/real-logic/simple-binary-encoding) - High Performance Message Codec.
* [DataSketches](https://datasketches.github.io/) - A Java software library of stochastic streaming algorithms.
* [stormpot ★103](https://github.com/chrisvest/stormpot) - A fast object pool for the JVM.
* [stream-lib ★1561](https://github.com/addthis/stream-lib) - A Java library for summarizing data in streams for which it is infeasible to store all events.
* [TraneIO](http://trane.io/) - High-performance implementation of the Future abstraction.
* [java-string-similarity ★1215](https://github.com/tdebatty/java-string-similarity) - String similarity and distance measures, including Levenshtein edit distance and sibblings, Jaro-Winkler, Longest Common Subsequence, cosine similarity etc.
* [transducers-java ★96 ⏳1Y](https://github.com/cognitect-labs/transducers-java) - Composable algorithmic transformations independent from the context of their input and output sources.
* [Zero-Allocation-Hashing ★216](https://github.com/OpenHFT/Zero-Allocation-Hashing) - Hashing any sequences of bytes in Java, including all kinds of primitive arrays, buffers, CharSequences and more.

## Metaprogramming

*Parsers, interpreters, compilers and source generation targeted for the JVM.*

* [Antlr](http://www.antlr.org/) - Parser generator for reading, processing, executing, or translating structured text or binary files.
* [auto ★4896](https://github.com/google/auto) - A collection of source code generators for Java.
* [Apache Calcite](http://calcite.apache.org/docs/) - Dynamic data management framework and SQL parser plugin.
* [Checker Framework](http://types.cs.washington.edu/checker-framework/) - Compiler plug-ins that find bugs or verify their absence.
* [compile-testing ★343](https://github.com/google/compile-testing) - Testing tools for javac and annotation processors.
* [derive4j ★250](https://github.com/derive4j/derive4j) - Algebraic data types constructors, pattern-matching, morphisms, optics and typeclasses.
* [error-prone ★2550](https://github.com/google/error-prone) - Catch common Java mistakes as compile-time errors.
* [GHCVM](https://github.com/rahulmutt/ghcvm) - A Haskell to JVM compiler that supports GHC Haskell.
* [Graal](http://openjdk.java.net/projects/graal/) - New experimental just-in-time compiler for Java that is integrated with the HotSpot virtual machine.
* [immutables](http://immutables.github.io/) - Generate simple, safe and consistent value objects.
* [javacc](https://javacc.java.net/) - Parser generator for use with Java.
* [javaparser ★1051](https://github.com/javaparser/javaparser) - Java 1.8 Parser and Abstract Syntax Tree for Java.
* [JavaPoet ★3357](https://github.com/square/javapoet) - A Java API for generating .java source files.
* [jparsec ★167](https://github.com/jparsec/jparsec) - Builds mini parsers in pure Java a la Haskell Parsec.
* [JSweet](http://www.jsweet.org/) - A transpiler from Java to TypeScript/JavaScript.
* [MPS](https://www.jetbrains.com/mps/) - Design and build extensible DSLs and editors.
* [parboiled ★991](https://github.com/sirthias/parboiled) - Parsing of arbitrary input text based on parsing expression grammars.
* [Sulong ★304](https://github.com/graalvm/sulong) - LLVM IR interpreter written in Java using Truffle and Graal.
* [TeaVM](https://github.com/konsoletyper/teavm) - Ahead-of-time translating compiler (transpiler) from Java bytecode to JavaScript.
* [Truffle](https://github.com/graalvm/truffle) - Framework for implementing languages as simple interpreters.
* [Xtext](https://eclipse.org/Xtext/) - Framework for development of programming languages and DSLs.

## Native

*Interconnecting JVM and native code* 

* [hawtjni ★60](https://github.com/fusesource/hawtjni) - A JNI code generator based on the JNI generator used in Eclipse SWT.
* [j2v8 ★622](https://github.com/eclipsesource/j2v8) - Java API for Google's V8 JavaScript engine.
* [JavaCPP ★1928](https://github.com/bytedeco/javacpp) - JavaCPP provides efficient access to native C++ inside Java.
* [jnr-ffi ★406](https://github.com/jnr/jnr-ffi) - Load native libraries without writing JNI code by hand.
* [jssembly ★103](https://github.com/dvx/jssembly) - Execution of native assembly from Java.
* [NuProcess ★210](https://github.com/brettwooldridge/NuProcess) - A low-overhead, non-blocking I/O, external Process execution implementation for Java.
* [Project Panama](http://openjdk.java.net/projects/panama/) - Enriching the connections between the JVM and APIs used by C programmers.

## Network

*Tools for network programming, packet capture, monitoring, testing and resiliency.*

* [Aeron ★2721](https://github.com/real-logic/Aeron) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport.
* [armeria ★750](https://github.com/line/armeria) - Asynchronous RPC/API client/server library built on top of Java 8, Netty 4.1, HTTP/2, and Thrift.
* [comcast ★4707](https://github.com/tylertreat/comcast) - Simulating shitty network connections.
* [gor](https://github.com/buger/gor) - HTTP traffic replay in real-time.
* [gRPC](http://www.grpc.io/) - A high performance, open source, general RPC framework that puts mobile and HTTP/2 first.
* [jRT ★24](https://github.com/LatencyUtils/jRT) - Measures response time of a java application to socket-based requests.
* [K3PO ★28](https://github.com/k3po/k3po) - Create arbitrary network traffic and behavior to certify whether a network endpoint behaves correctly.
* [muxy ★550](https://github.com/mefellows/muxy) - Simulating real-world distributed system failures.
* [Netty](http://netty.io/) - Async event-driven network library for high performance protocol servers & clients.
* [okhttp ★19414](https://github.com/square/okhttp) - An HTTP+HTTP/2 client for Android and Java applications.
* [ReactiveSocket](http://reactivesocket.io/) - ReactiveSocket is an application protocol providing Reactive Streams semantics over an asynchronous, binary boundary.
* [SimianArmy ★5410](https://github.com/Netflix/SimianArmy) - Resiliency tool that helps ensure that your applications can tolerate random instance failures.
* [pcap4j ★309](https://github.com/kaitoy/pcap4j) - Java library for capturing, crafting, and sending packets using libpcap.
* [pig ★272](https://github.com/rafael-santiago/pig) - A Linux packet crafting tool.
* [tcpdump](http://www.tcpdump.org/) - Packet analyzer for network traffic capture.
* [tcpflow ★658](https://github.com/simsong/tcpflow) - Captures TCP connections flows in a way that is convenient for protocol analysis and debugging.
* [tcpreplay ★221](https://github.com/appneta/tcpreplay) - Pcap editing and replay tools.

## Nix tools

*Useful *nix tools when profiling the JVM and interaction with the host environment*
* [atoptool](http://www.atoptool.nl/) - Logging of system and process activity for long-term analysis, highlighting overloaded system.
* [Flame Graphs](http://www.brendangregg.com/flamegraphs.html) - Visualization of profiled software, allowing the most frequent code-paths to be identified quickly and accurately.
* [javap](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/javap.html) - Disassembles class files into code that reflects the java bytecode.
* [jhat](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jhat.html) - Java Heap Analysis Tool
* [jinfo](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jinfo.html) - Prints configuration information for a given process.
* [jstack](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jstack.html) - Prints stack traces of threads for a given Java process.
* [jstat](https://docs.oracle.com/javase/8/docs/technotes/tools/unix/jstat.html) - Monitors GC and compiler statistics in the JVM.
* [hwloc](http://linux.die.net/man/7/hwloc) - Reports the structure of the processor, number of cores, hyperthreads and cache size.
* [likwid ★392](https://github.com/RRZE-HPC/likwid) - Read hardware performance counters on Intel and AMD processors.
* [numactl](http://linux.die.net/man/8/numactl) - Control NUMA policy for processes or shared memory.
* [oprofile](http://oprofile.sourceforge.net/news/) - System-wide hardware performance monitoring with easy-to-use interface at low overhead.
* [perf](https://perf.wiki.kernel.org/index.php/Main_Page) - Linux profiling with performance counters.
* [perf-tools](https://github.com/brendangregg/perf-tools) - Performance analysis tools based on Linux perf_events (aka perf) and ftrace.
* [sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.
* [sysstat](http://sebastien.godard.pagesperso-orange.fr) - Performance monitoring tools for Linux.
* [taskset](http://linuxcommand.org/man_pages/taskset1.html) - Retrieve or set a processes’s CPU affinity.


## Profilers

*Tools that provide profiling and tracing information to aid program optimization*

* [allocation-instrumenter ★195](https://github.com/google/allocation-instrumenter) - Java agent that rewrites bytecode to instrument allocation sites.
* [aprof ★92](https://github.com/Devexperts/aprof) - Java memory allocation profiler.
* [BTrace](https://github.com/jbachorik/btrace) - a safe, dynamic tracing tool for the Java platform.
* [Chronon](http://chrononsystems.com) - Record your entire java program. Replay on any machine.
* [GCViewer ★1664](https://github.com/chewiebug/GCViewer) - GCViewer is a tool that visualizes verbose GC output.
* [hawkshaw ★38 ⏳1Y](https://github.com/jClarity/hawkshaw) - Tools for tracking down memory / JVM problems & generating predictable-as-possible VM behaviour.
* [HdrHistogram](http://hdrhistogram.github.io/HdrHistogram/) - A Histogram that supports recording and analyzing sampled data value counts.
* [hdrhistogram-metrics-reservoir](https://bitbucket.org/marshallpierce/hdrhistogram-metrics-reservoir) - A Metrics Reservoir implementation backed by HdrHistogram.
* [HdrLogProcessing ★19](https://github.com/nitsanw/HdrLogProcessing) - Utilities for HDR Histogram logs manipulation.
* [heapster ★326](https://github.com/mariusae/heapster) - Production heap profiling for the JVM.
* [honest-profiler](https://github.com/RichardWarburton/honest-profiler) - Sampling JVM profiler without the safepoint sample bias.
* [jamm ★374](https://github.com/jbellis/jamm) - Measure actual object memory use including JVM overhead.
* [Java Flight Recorder (JFR)](http://www.oracle.com/technetwork/java/javaseproducts/mission-control/java-mission-control-1998576.html) - Tool for collecting diagnostic and profiling data about a running Java application with almost no performance overhead.
* [java-sizeof ★95 ⏳1Y](https://github.com/dweiss/java-sizeof) - Memory consumption estimator for Java.
* [jcstress](http://openjdk.java.net/projects/code-tools/jcstress/) - Experimental harness and tests to aid the research in the correctness of concurrency support in the JVM, class libraries, and hardware.
* [jfr-flame-graph ★81](https://github.com/chrishantha/jfr-flame-graph) - Converting JFR Method Profiling Samples to FlameGraph compatible format.
* [jitwatch ★1094](https://github.com/AdoptOpenJDK/jitwatch) - Log analyser / visualiser for Java HotSpot JIT compiler.
* [jitwatch-intellij ★131](https://github.com/yole/jitwatch-intellij) - JITWatch plugin for IntelliJ IDEA.
* [jHiccup](http://www.azul.com/jhiccup/) - jHiccup is an open source tool designed to measure the pauses and stalls associated with an application’s underlying Java runtime platform.
* [jmh](http://openjdk.java.net/projects/code-tools/jmh/) - Micro benchmarks written in Java and other languages targetting the JVM.
* [jmh-compare-gui ★45](https://github.com/akarnokd/jmh-compare-gui) - GUI for comparing JMH results.
* [JOL](http://openjdk.java.net/projects/code-tools/jol/) - Analyze actual object layout schemes, footprint, and references in JVMs.
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html) - Helps resolve performance bottlenecks, pin down memory leaks and understand threading issues.
* [JVMTI](https://docs.oracle.com/javase/8/docs/technotes/guides/jvmti/) - Provide a native API to inspect the state and to control the execution of applications running in the JVM.
* [jvmtop ★511](https://github.com/patric-r/jvmtop) - Lightweight console application to monitor running jvms on a machine in top-like manner.
* [MAT](https://eclipse.org/mat/) - Java heap analyzer that help find memory leaks and reduce memory consumption.
* [leakcanary ★14847](https://github.com/square/leakcanary) - A memory leak detection library for Android and Java.
* [metrics](http://metrics.dropwizard.io/) - Measure the behavior of critical components in production environment.
* [Overseer](http://www.peternier.com/projects/overseer/overseer.php) - Low-Level Hardware Monitoring and Management for Java.
* [perf-map-agent](https://github.com/jrudolph/perf-map-agent) - Generate method mappings to use with the linux `perf` tool.
* [perfj ★279 ⏳1Y](https://github.com/coderplay/perfj) - Linux perf for java programs.
* [polarbear ★18 ⏳4Y](https://github.com/Cue/polarbear) - A tool to help diagnose OutOfMemoryError conditions.
* [Riemann JVM Profiler ★257 ⏳2Y](https://github.com/riemann/riemann-jvm-profiler) - JVM agent which sends function-level profiler telemetry to a Riemann server for analysis, visualization, and storage.
* [statsd-jvm-profiler ★233](https://github.com/etsy/statsd-jvm-profiler) - JVM agent profiler that sends profiling data to StatsD.
* [Swiss Java Knife ★1324](https://github.com/aragozin/jvm-tools) - Small set of tools for JVM troublshooting, monitoring and profiling.
* [Takipi](https://www.takipi.com/) - Tells you when and why code breaks in production.
* [Tracer ★48](https://github.com/zalando/tracer) - Manages custom trace identifiers and carries them through distributed systems.
* [YourKit](https://www.yourkit.com/) - Fully featured, easy to use, low overhead profiler.
* [Zipkin ★5667](https://github.com/openzipkin/zipkin) - A distributed tracing system gather timing data for disparate services developed by Twitter.


## Runtimes

*Tools for managing jvm runtime processes*
* [Capsule ★1021](https://github.com/puniverse/capsule) - Dead-Simple Packaging and Deployment for JVM Apps.
* [CRaSH](http://www.crashub.org/) - The shell for the Java Platform.
* [Drip ★1379 ⏳1Y](https://github.com/ninjudd/drip) - Fast JVM launching without the hassle of persistent JVMs.
* [HotswapAgent ★733](https://github.com/HotswapProjects/HotswapAgent) - Redefine classes at runtime and skip the redeploy process.
* [jvmkill ★41](https://github.com/airlift/jvmkill) - Agent that forcibly terminates the JVM when it is unable to allocate memory or create a thread.
* [Nailgun](http://martiansoftware.com/nailgun/) - Nailgun is a client, protocol, and server for running Java programs from the command line without incurring the JVM startup overhead.

## Virtual Machines

*Virtual machines that implement the JVM specification or parts of it.*
* [Avian ★911](https://github.com/ReadyTalk/avian) - Lightweight highly portable JVM with an option for AOT compilation.
* [Dalvik](https://source.android.com/devices/tech/dalvik/) - Android runtime (ART) is the managed runtime used by applications and some system services on Android.
* [DCEVM](http://dcevm.github.io) - Modification of Java HotSwap VM with unlimited support for reloading classes at runtime.
* [HotSpot](http://openjdk.java.net/groups/hotspot/) - HotSpot virtual machine maintained and distributed by Oracle Corporation.
* [IBM J9](http://www.ibm.com/developerworks/java/jdk/) - JVM developed by IBM.
* [J2ObjC ★4722](https://github.com/google/j2objc) - Translator from Java source to Objective-C code. Keeps shared code between iOS native apps and Android native apps. 
* [jvm.go ★1843](https://github.com/zxh0/jvm.go) - A JVM written in Go.
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - An Open Source Java bytecode to C translator for iOS native development. Designed as a part of the [Codename One](https://www.codenameone.com/) WORA for mobile project.
* <strike>[RoboVM](https://robovm.com/) - Create native iOS and Android apps in Java.</strike> - Discontinued
* [Zing](https://www.azul.com/products/zing/) - The only JVM that eliminates Java garbage collection pauses for large heap sizes.
* [Zulu](https://www.azul.com/products/zulu/) - The only certified multi-platform build of OpenJDK: Free, 100% open source Java.

# Resources

## Documentation

*Documentation related to JVM*
* [Coordinated Omission problem](https://groups.google.com/forum/#!msg/mechanical-sympathy/icNZJejUHfE/BfDekfBEs_sJ) - Discussion on Mechanical Sympathy.
* [False sharing](http://mechanical-sympathy.blogspot.se/2011/07/false-sharing.html) - Threads impact the performance of each other while modifying independent variables sharing the same cache line. Martin Thompson.
* [The JVM specification](https://docs.oracle.com/javase/specs/jvms/se8/jvms8.pdf) - The Java Virtual
Machine Specification Java SE 8 Edition.
* [The Java Memory Model](http://www.cs.umd.edu/~pugh/java/memoryModel/) - Starting point for discussions of and information concerning the Java Memory Model.
* [The JSR-133 Cookbook for Compiler Writers](http://gee.cs.oswego.edu/dl/jmm/cookbook.html) - Unofficial guide to implementing the new Java Memory Model (JMM) specified by JSR-133.
* [Garbage Collection Tuning Guide](http://docs.oracle.com/javase/8/docs/technotes/guides/vm/gctuning/) - HotSpot Virtual Machine Garbage Collection Tuning Guide.
* [Safepoints](http://psy-lob-saw.blogspot.se/2014/03/where-is-my-safepoint.html) - Where is my safepoint? Nitsan Wakart.  
* [Topics in High-Performance Messaging](https://www.informatica.com/downloads/1568_high_perf_messaging_wp/Topics-in-High-Performance-Messaging.htm) - Design decisions, experience and constraints explained in high performance messaging systems.
* [Top 10 Performance Mistakes](http://www.infoq.com/articles/top-10-performance-mistakes) - Digest of the top 10 performance related mistakes Martin Thompson has seen in production.
* [The USE method](http://www.brendangregg.com/usemethod.html) - The Utilization Saturation and Errors (USE) Method is a methodology for analyzing the performance of any system. Brendan Gregg.
* [An introduction to distributed systems](https://github.com/aphyr/distsys-class) - Kyle Kingsbury (author of Jepsen).
* [Using JDK 9 Memory Order Modes](http://gee.cs.oswego.edu/dl/html/j9mm.html) - For expert programmers familiar with Java concurrency, but unfamiliar with the memory order modes available in JDK 9 provided by VarHandles.

## Communities

*Active discussions.*

* [concurrency-interest](http://altair.cs.oswego.edu/mailman/listinfo/concurrency-interest) - Discussion list for JSR-166.
* [hotspot-compiler-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-compiler-dev) - Technical discussion about the development of the HotSpot bytecode compilers.
* [hotspot-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-dev) - HotSpot development mailing list.
* [hotspot-gc-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-gc-dev) - Technical discussion about the development of the HotSpot garbage collectors.
* [mechanical-sympathy](https://groups.google.com/forum/#!forum/mechanical-sympathy) - Discussing how to code sympathetically to and measure the underlying stack/platform so good performance can be extracted.
* [Performance Java User's Group](https://plus.google.com/u/0/communities/107178245817384004088/) - For expert Java *developers* who want to push their systems to the next level
* [Virtual Machine Meetup](http://vmmeetup.github.io/2015/) - Venue for discussing the latest research and developments in the area of managed language execution. 

## Media

*Videos, podcasts and other media related to JVMs*
* [Extreme Profiling: Digging Into Hotspots](https://youtu.be/7PkkxDaFDj8?list=PLKuh52zVrL6l6jzeSwNce77yLdfKmHAgD) - Nitsan Wakart.
* [Java vs. C Performance](http://www.infoq.com/presentations/java-vs-c-performance) - Cliff Click.
* [Why JNI is slow?](https://www.youtube.com/watch?v=LoyBTqkSkZk) - Cliff Click
* [A Crash Course in Modern Hardware](https://www.youtube.com/watch?v=OFgxAFdxYAQ) - Cliff Click
* [Java Profiling from the Ground Up](https://www.youtube.com/watch?v=_6vJyciXkwo) - Nitsan Wakart.
* [The Illusion of Execution](https://www.youtube.com/watch?v=3g9R-RVIkOE) - Nitsan Wakart.
* [Mythbusting Modern Hardware to Gain 'Mechanical Sympathy'](https://www.youtube.com/watch?v=MC1EKLQ2Wmg) - Martin Thompson.
* [Designing for Performance](https://www.youtube.com/watch?v=fDGWWpHlzvw) - Martin Thompson.
* [How NOT to Measure Latency](https://www.youtube.com/watch?v=lJ8ydIuPFeU) - Gil Tene.
* [JVM Language Summit 2015](http://openjdk.java.net/projects/mlvm/jvmlangsummit/) - JVM Language Summit 2015.
* [JVM Language Summit 2016](https://www.youtube.com/playlist?list=PLX8CzqL3ArzUY6rQAQTwI_jKvqJxrRrP_) - JVM Language Summit 2016.
* [Bits of advice for VM writers](https://www.youtube.com/watch?v=vzzABBxo44g) - Cliff Click.
* [Understanding Java garbage collection ...](https://www.youtube.com/watch?v=_e5hujoTkgY) - Gil Tene.
* [Faster Object Arrays](https://www.youtube.com/watch?v=bZuPTCaciLU) - Gil Tene at GOTO Conferences.
* [Java Memory Model Pragmatics](https://www.youtube.com/watch?v=TxqsKzxyySo) - Aleksey Shipilev.
* [With GC Solved, What Else Makes a JVM Pause?](https://www.youtube.com/watch?v=Y39kllzX1P8) - John Cuthbertson.
* [JVM Mechanics](https://vimeo.com/120533011) - Douglas Hawkins.
* [Give me 15 minutes and I'll change your view of Linux tracing](https://www.youtube.com/watch?v=GsMs3n8CB6g) - Brendan Gregg.

## People

*People that influence JVM development and/or the community around it*
* [Aleksey Shipilëv](http://shipilev.net/) - Developing Oracle/Open JDK/Hotspot and other Java-related technologies.
* [Brian Goetz](https://twitter.com/BrianGoetz) - Java Language Architect at Oracle.
* [Ben Christensen](https://twitter.com/benjchristensen) - Facebook, Netflix, Apple engineering.
* [Brendan Gregg](http://www.brendangregg.com) - Cloud performance, kernel engineer, speaker, author.
* [Charles Nutter](https://twitter.com/headius) - JRuby guy.
* [Cliff Click](http://www.cliffc.org/blog/) - Creator of the HotSpot Server Compiler.
* [Dave Dice](https://blogs.oracle.com/dave/) - Senior research scientist in the Scalable Synchronization Research Group within Oracle.
* [Dávid Karnok](http://akarnokd.blogspot.se/) - RxJava committer that blogs about advanced RxJava.
* [Doug Lea](http://g.oswego.edu/) - Author of the Java memory model.
* [Gil Tene](https://twitter.com/giltene) - Azul Systems.
* [John Rose](https://blogs.oracle.com/jrose/) - HotSpot developer.
* [Jonas Bonér](https://twitter.com/jboner) - Founder & CTO of Lightbend.
* [Marcus Lagergren](https://twitter.com/lagergren) - Java language team alumnus.
* [Mark Reinhold](https://twitter.com/mreinhold) - Chief Architect, Java Platform Group, Oracle.
* [Martin Thompson](http://mechanical-sympathy.blogspot.se/) - Pasty faced performance gangster.
* [Martijn Verburg](https://twitter.com/karianna) - Java Champion.
* [Nitsan Wakart](http://psy-lob-saw.blogspot.se/2014/03/where-is-my-safepoint.html) - Azul Systems.
* [Norman Maurer](https://twitter.com/normanmaurer) - Netty developer.
* [Paul Phillips](https://twitter.com/extempore2) - Forever undisputed SLOC Scala compiler dev.
* [Peter Lawrey](https://twitter.com/PeterLawrey) - Innovative developer of high performance Java systems for competitive advantage.
* [Richard Warburton](https://twitter.com/RichardWarburto) - Developer, Speaker, Author.
* [Todd L. Montgomery](https://twitter.com/toddlmontgomery) - Ex-CTO, Ex-NASA researcher, network geek, messaging middleware designer.
* [Stéphane Maldini](https://twitter.com/smaldini) - Project Reactor Lead @Pivotal.
* [Stuart Marks](https://twitter.com/stuartmarks) - Doctor Deprecator. Java/JDK/OpenJDK developer 
* [Viktor Klang](https://twitter.com/viktorklang) - Deputy CTO at Typesafe Inc.

# Contributing

Contributions are very welcome!

Please have a look at [contributing.md](https://github.com/deephacks/awesome-jvm/blob/master/contributing.md) for guidelines.
---
<p align="center">
	This list is a copy of <a href="https://github.com/deephacks/awesome-jvm">https://github.com/deephacks/awesome-jvm</a> with ranks
</p>