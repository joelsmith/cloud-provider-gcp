load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "conversion.go",
        "defaults.go",
        "doc.go",
        "helpers.go",
        "register.go",
        "zz_generated.conversion.go",
        "zz_generated.defaults.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kubernetes/pkg/apis/certificates/v1beta1",
    importpath = "k8s.io/kubernetes/pkg/apis/certificates/v1beta1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/certificates/v1beta1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/conversion:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/sets:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/certificates:go_default_library",
    ],
)
