load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "ascii.go",
        "case.go",
        "legal.go",
        "mime.go",
        "notwords.go",
        "replace.go",
        "stringreplacer.go",
        "url.go",
        "words.go",
    ],
    importmap = "github.com/kubernetes-sigs/poseidon/vendor/github.com/client9/misspell",
    importpath = "github.com/client9/misspell",
    visibility = ["//visibility:public"],
)
