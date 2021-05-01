load("@rules_cc//cc:defs.bzl", "cc_test")

cc_test(
  name = "data_fitter_test",
  size = "small",
  srcs = glob(["*.cpp"]),
  deps = [
    "@com_google_googletest//:gtest_main",
    "//lib:DataFitterLib"
  ],
)