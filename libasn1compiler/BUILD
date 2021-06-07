load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "libasn1compiler",
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
        "-Ilibasn1compiler",
        "-Ilibasn1fix",
        "-Ilibasn1parser",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//libasn1fix:libasn1fix",
        "//libasn1parser:libasn1parser",
    ],
)