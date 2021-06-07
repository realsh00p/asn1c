load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "libasn1fix",
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
        "-Ilibasn1fix",
        "-Ilibasn1parser",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//libasn1parser:libasn1parser",
    ],
)