workspace(name = "libunwind-bazel")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "libunwind",
    build_file = "@libunwind-bazel//:BUILD.libunwind",
    sha256 = "8455011c33b14abfe57b2fd9803fb610316b16d4c9818bec552287e2ba68922f",
    strip_prefix = "libunwind-11.0.0.src",
    url = "https://github.com/llvm/llvm-project/releases/download/llvmorg-11.0.0/libunwind-11.0.0.src.tar.xz",
)
