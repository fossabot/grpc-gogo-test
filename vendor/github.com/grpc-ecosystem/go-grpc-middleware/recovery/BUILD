load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "interceptors.go",
        "options.go",
    ],
    importmap = "github.com/iwaltgen/grpc-gogo-test/vendor/github.com/grpc-ecosystem/go-grpc-middleware/recovery",
    importpath = "github.com/grpc-ecosystem/go-grpc-middleware/recovery",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/net/context:go_default_library",
        "//vendor/google.golang.org/grpc:go_default_library",
        "//vendor/google.golang.org/grpc/codes:go_default_library",
    ],
)
