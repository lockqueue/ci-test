load("@rules_license//rules:license.bzl", "license")

license(
    name = "license",
    package_name = "lockqueue/test",
    copyright_notice = "Copyright © 2014 The lockqueue-test Authors. All rights reserved.",
    license_kinds = [
        "@rules_license//licenses/spdx:Apache-2.0",
    ],
    license_text = "LICENSE",
)

exports_files(["LICENSE"])

filegroup(
    name = "srcs",
    srcs = glob(
        ["**/*"],
        exclude = [
            "bazel-*",
            ".*",
        ],
    ),
    applicable_licenses = [":license"],
    visibility = ["//tools/oss-compliance:__pkg__"],
)
