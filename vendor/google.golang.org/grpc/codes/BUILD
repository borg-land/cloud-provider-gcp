load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "codes",
    srcs = [
        "code_string.go",
        "codes.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/codes",
    importpath = "google.golang.org/grpc/codes",
    visibility = ["//visibility:public"],
)
