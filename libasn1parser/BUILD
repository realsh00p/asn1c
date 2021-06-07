load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "libasn1parser",
    srcs = glob([
        "*.c",
    ]),
    hdrs = glob([
        "*.h"
    ]),
    copts = [
        "-g",
        "-O3",
        "-fPIC",
        "-DHAVE_CONFIG_H=1",
        "-Ilibasn1parser",
    ],
    visibility = ["//visibility:public"],
)
