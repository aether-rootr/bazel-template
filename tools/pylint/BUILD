py_binary(
    name = "check_style",
    srcs = ["check_style.py"],
    data = [
        ".pylintrc",
    ],
    deps = [
        "@astroid_py//:astroid",
        "@isort_py//:isort",
        "@pylint_py//:pylint",
    ],
)