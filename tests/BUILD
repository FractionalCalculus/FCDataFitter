#load("@rules_cc//cc:defs.bzl", "cc_test")

cc_test(
  name = "data_fitter_test",
  size = "small",
  srcs = glob(["*.cpp"]),
  deps = [
    "//googletest:gtest_main",
    "//lib:DataFitterLib"
  ],
)