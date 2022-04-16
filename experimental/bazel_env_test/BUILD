load("@rules_python//python:defs.bzl", "py_library")
load("@python_deps//:requirements.bzl", "requirement")
load("@subpar//:subpar.bzl", "par_binary")

par_binary(
    name = "test",
    srcs = ["test.py"],
    deps = [
        requirement("click"),
        requirement("flask")
    ]
)
