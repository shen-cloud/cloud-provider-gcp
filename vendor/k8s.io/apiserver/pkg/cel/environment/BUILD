load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "environment",
    srcs = [
        "base.go",
        "environment.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/cel/environment",
    importpath = "k8s.io/apiserver/pkg/cel/environment",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/cel-go/cel",
        "//vendor/github.com/google/cel-go/ext",
        "//vendor/golang.org/x/sync/singleflight",
        "//vendor/k8s.io/apimachinery/pkg/util/version",
        "//vendor/k8s.io/apiserver/pkg/apis/cel",
        "//vendor/k8s.io/apiserver/pkg/cel",
        "//vendor/k8s.io/apiserver/pkg/cel/library",
    ],
)
