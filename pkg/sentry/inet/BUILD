package(
    default_visibility = ["//:sandbox"],
    licenses = ["notice"],
)

load("//tools/go_stateify:defs.bzl", "go_library")

go_library(
    name = "inet",
    srcs = [
        "context.go",
        "inet.go",
        "test_stack.go",
    ],
    importpath = "gvisor.googlesource.com/gvisor/pkg/sentry/inet",
    deps = ["//pkg/sentry/context"],
)
