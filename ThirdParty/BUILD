cc_library(
  name = "Catch2",
  srcs = ["Catch2.cc"],
  hdrs = ["Catch2.hh"],
  linkstatic = True,
  visibility = ["//visibility:public"],
)

cc_library(
  name = "Eigen",
  hdrs = ["Eigen.hh"],
  copts = ["-Iexternal/eigen"],
  visibility = ["//visibility:public"],
  deps = [
    "@eigen",
  ]
)
