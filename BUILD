package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load("@io_bazel_rules_go//go:def.bzl", "gazelle", "go_prefix")

go_prefix("istio.io/core")

gazelle(name = "gazelle")

filegroup(
    name = "generate_word_list",
    srcs = ["mixer/bin/generate_word_list.py"],
)
