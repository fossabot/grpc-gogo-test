package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["greeter.go"],
    importpath = "github.com/iwaltgen/grpc-gogo-test/pkg/gogoserver/grpc/service",
    deps = [
        "//proto/v1:go_default_library",
        "//vendor/github.com/gogo/protobuf/types:go_default_library",
    ],
)
