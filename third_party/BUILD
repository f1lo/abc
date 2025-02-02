load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
  name = "glad",
  srcs = ["glad.c"],
  hdrs = ["glad/glad.h", "glad/khrplatform.h"],
  # Required for angled brackets include in glad.c
  includes = [""],
  visibility = ["//visibility:public"],
)
