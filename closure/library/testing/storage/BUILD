# DO NOT EDIT -- bazel run //closure/library:regenerate -- "$PWD"

package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load("//closure:defs.bzl", "closure_js_library")

closure_js_library(
    name = "fakemechanism",
    testonly = True,
    srcs = ["@com_google_javascript_closure_library//:closure/goog/testing/storage/fakemechanism.js"],
    lenient = True,
    deps = [
        "//closure/library/storage/mechanism:iterablemechanism",
        "//closure/library/structs:map",
    ],
)
