load("@rules_python//python:pip.bzl", "compile_pip_requirements")

# If add new python library to requirments
# please run bazel run //third_party:requirements.update

compile_pip_requirements(
    name = "requirements",
    extra_args = ["--allow-unsafe"],
    requirements_in = "requirements.txt",
    requirements_txt = "requirements_lock.txt",
)