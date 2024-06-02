load("@rules_qt//:qt.bzl", "qt_cc_library")

package(default_visibility = ["//visibility:public"])

qt_cc_library(
    name = "qwt",
    srcs = glob(["*.cpp"]),
    hdrs = glob(["*.h"]) + glob(["classincludes/**"]),
    visibility = ["//visibility:public"],
    includes = ["."],
    deps = [
        "@rules_qt//:qt",
    ],
)
