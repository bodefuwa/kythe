load("//tools/build_rules/go", "go_package")

package(default_visibility = ["//kythe:default_visibility"])

go_package(
    test_deps = [
        "//kythe/go/util/schema",
    ],
    deps = [
        "//kythe/go/services/web",
        "//kythe/proto:xref_proto",
        "//third_party/go:context",
    ],
)
