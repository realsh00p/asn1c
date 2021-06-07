load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_library(
    name = "skeletons",
    srcs = glob([
        "*.c",
        "*.h",
    ]),
    hdrs = glob([
        "*.h"
    ]),
    copts = [
        "-g",
        "-O3",
        "-fPIC",
        "-DHAVE_CONFIG_H=1",
    ],
    visibility = ["//visibility:public"],
)
