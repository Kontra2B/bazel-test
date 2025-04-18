load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "spdlog",
    urls = ["https://github.com/gabime/spdlog/archive/refs/tags/v1.13.0.tar.gz"],
    strip_prefix = "spdlog-1.13.0",
    sha256 = "534f2ee1a4dcbeb22249856edfb2be76a1cf4f708a20b0ac2ed090ee24cfdbc9",
	build_file = "//dep:BUILD.bazel",
)

http_archive(
    name = "gtest",
    url = "https://github.com/google/googletest/archive/refs/tags/v1.14.0.zip",
    strip_prefix = "googletest-1.14.0",
    sha256 = "1f357c27ca988c3f7c6b4bf68a9395005ac6761f034046e9dde0896e3aba00e4",
)
