load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "addresses.go",
        "group.go",
        "legacy.go",
        "root.go",
        "storageversionhash.go",
        "util.go",
        "version.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/endpoints/discovery",
    importpath = "k8s.io/apiserver/pkg/endpoints/discovery",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/emicklei/go-restful:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/net:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/endpoints/handlers/negotiation:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/endpoints/handlers/responsewriters:go_default_library",
        "//vendor/k8s.io/klog:go_default_library",
    ],
)
