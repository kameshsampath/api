load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "value_type.pb.go",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "@com_github_gogo_protobuf//proto:go_default_library",
        "@com_github_gogo_protobuf//sortkeys:go_default_library",
    ],
)

filegroup(
    name = "go_default_library_protos",
    srcs = [
        "value_type.proto",
    ],
    visibility = ["//visibility:public"],
)
