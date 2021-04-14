load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(

name = "foolib",

hdrs = ["foo/foo.h"],
srcs = ["foo/foo.cpp"],

include_prefix = "trpc"


)


cc_library(
    name = "pig",
    srcs = ["pig/pig.cpp"],
    hdrs = ["pig/pig.h"],
    visibility = ["//visibility:public"],
    deps = ["foolib"]
)
