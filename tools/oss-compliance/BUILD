load("@rules_license//rules:compliance.bzl", "check_license")

check_license(
    name = "check_srcs",
    check_conditions = False,
    copyright_notices = "srcs_copyrights.txt",
    license_texts = "srcs_licenses.txt",
    report = "srcs_report",
    deps = [
        "//:srcs",
    ],
)
