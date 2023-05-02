# GH-464
https://github.com/netty/netty-incubator-codec-quic/issues/464

# How to run the example

## Server
- Specify `JAVA_HOME` to `graalvm`
- Go to `./server` folder
- Execute `mvn -Pnative package`
- Go to `./target` folder
- Execute `./quic-example-server`

## Client
- Specify `JAVA_HOME` to `graalvm`
- Go to `./client` folder
- Execute `mvn -Pnative package`
- Go to `./target` folder
- Execute `./quic-example-client`

# Notes
- The current version of this project has a dependency to `io.netty.incubator:netty-incubator-codec-native-quic` version `0.0.41.Final-SNAPSHOT`,
which has a fix for https://github.com/netty/netty-incubator-codec-quic/issues/464.
- This project has dependency to `org.graalvm.buildtools:graalvm-reachability-metadata`
