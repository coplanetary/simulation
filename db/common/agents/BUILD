java_library(
    name = "agents",
    srcs = glob([
        "base/*.java",
        "interaction/*.java",
        "utils/*.java",
        "world/*.java",
    ]),
    visibility = ["//visibility:public"],
    deps = [
        "//db/common/driver",
        "//db/common/world",
        "//utils",
        "@graknlabs_grabl_tracing//client",
        "@maven//:commons_cli_commons_cli",
        "@maven//:org_apache_commons_commons_csv",
        "@maven//:org_apache_commons_commons_lang3",
        "@maven//:org_slf4j_slf4j_api",
    ],
)
