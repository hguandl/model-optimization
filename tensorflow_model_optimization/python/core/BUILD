package(default_visibility = ["//visibility:public"])

licenses(["notice"])  # Apache 2.0

py_library(
    name = "core",
    srcs = ["__init__.py"],
    srcs_version = "PY3",
    deps = [
        ":version",
        "//tensorflow_model_optimization/python/core/clustering",
        "//tensorflow_model_optimization/python/core/internal",
        "//tensorflow_model_optimization/python/core/keras",
        "//tensorflow_model_optimization/python/core/quantization",
        "//tensorflow_model_optimization/python/core/sparsity",
    ],
)

py_library(
    name = "version",
    srcs = ["version.py"],
    srcs_version = "PY3",
)
