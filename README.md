# java-upgrade-toy

Repro steps
* Check this repo out
* bazel build //:x --javabase=//:jdk10-jdk --java_toolchain=@bazel_tools//tools/jdk:toolchain_java10 --host_java_toolchain=@bazel_tools//tools/jdk:toolchain_java10 --host_javabase=//:jdk10-jdk