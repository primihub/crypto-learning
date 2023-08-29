workspace(name = "crypto-learning")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
  name = "rules_cc",
  urls = ["https://github.com/bazelbuild/rules_cc/releases/download/0.0.1/rules_cc-0.0.1.tar.gz"],
  sha256 = "4dccbfd22c0def164c8f47458bd50e0c7148f3d92002cdb459c2a96a68498241",
)

http_archive(
  name = "openssl",
  url = "https://github.com/openssl/openssl/archive/refs/tags/OpenSSL_1_1_1o.tar.gz",
  strip_prefix = "openssl-OpenSSL_1_1_1o",
  build_file = "//bazel:openssl.BUILD",
)
