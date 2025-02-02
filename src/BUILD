load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")

platform(
    name = "windows",
    constraint_values = [
       "@platforms//cpu:x86_64",
       "@platforms//os:windows",
    ],
)

cc_binary(
  name = "main",
  srcs = ["main.cc"],
  deps = [
    "@glfw//:glfw",
    "//third_party:glad",
  ],
)