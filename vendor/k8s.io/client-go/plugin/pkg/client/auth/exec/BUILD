load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "exec",
    srcs = [
        "exec.go",
        "metrics.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/plugin/pkg/client/auth/exec",
    importpath = "k8s.io/client-go/plugin/pkg/client/auth/exec",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/davecgh/go-spew/spew",
        "//vendor/golang.org/x/term",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer",
        "//vendor/k8s.io/apimachinery/pkg/util/net",
        "//vendor/k8s.io/client-go/pkg/apis/clientauthentication",
        "//vendor/k8s.io/client-go/pkg/apis/clientauthentication/install",
        "//vendor/k8s.io/client-go/pkg/apis/clientauthentication/v1:clientauthentication",
        "//vendor/k8s.io/client-go/pkg/apis/clientauthentication/v1beta1",
        "//vendor/k8s.io/client-go/tools/clientcmd/api",
        "//vendor/k8s.io/client-go/tools/metrics",
        "//vendor/k8s.io/client-go/transport",
        "//vendor/k8s.io/client-go/util/connrotation",
        "//vendor/k8s.io/klog/v2:klog",
        "//vendor/k8s.io/utils/clock",
    ],
)
