load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "batch",
    srcs = [
        "cronjob.go",
        "cronjobspec.go",
        "cronjobstatus.go",
        "job.go",
        "jobcondition.go",
        "jobspec.go",
        "jobstatus.go",
        "jobtemplatespec.go",
        "podfailurepolicy.go",
        "podfailurepolicyonexitcodesrequirement.go",
        "podfailurepolicyonpodconditionspattern.go",
        "podfailurepolicyrule.go",
        "uncountedterminatedpods.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/applyconfigurations/batch/v1",
    importpath = "k8s.io/client-go/applyconfigurations/batch/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/batch/v1:batch",
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/managedfields",
        "//vendor/k8s.io/client-go/applyconfigurations/core/v1:core",
        "//vendor/k8s.io/client-go/applyconfigurations/internal",
        "//vendor/k8s.io/client-go/applyconfigurations/meta/v1:meta",
    ],
)
