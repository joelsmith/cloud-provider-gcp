load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["srv.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.etcd.io/etcd/pkg/srv",
    importpath = "go.etcd.io/etcd/pkg/srv",
    visibility = ["//visibility:public"],
    deps = ["//vendor/go.etcd.io/etcd/pkg/types:go_default_library"],
)
