load("@rules_java//java:defs.bzl", "java_library")

package(default_visibility = ["//src:__subpackages__"])

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
)

java_library(
    name = "stable_sort",
    srcs = glob(["*.java"]),
    deps = [
        "//src/main/java/com/google/devtools/build/lib/util/io",
        "//src/main/protobuf:spawn_java_proto",
        "//third_party:guava",
    ],
)
