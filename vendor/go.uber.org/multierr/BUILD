load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["error.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.uber.org/multierr",
    importpath = "go.uber.org/multierr",
    visibility = ["//visibility:public"],
    deps = ["//vendor/go.uber.org/atomic:go_default_library"],
)
