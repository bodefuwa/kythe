load("//tools/build_rules/go", "go_package")

package(default_visibility = ["//kythe:default_visibility"])

go_package(
    test_deps = [
        "//kythe/proto:analysis_proto",
        "//kythe/proto:storage_proto",
        "//third_party/go:context",
        "//third_party/go:protobuf",
    ],
    deps = [
        "//kythe/go/platform/analysis",
        "//third_party/go:context",
        "//third_party/go:uuid",
    ],
)
