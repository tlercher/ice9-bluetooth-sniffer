# A list of available rules and their signatures can be found here: https://buck2.build/docs/api/rules/


# Our actual targets

cxx_binary(
    name = "ice9-bluetooth",
    srcs = ["main.c"],
    link_style = "static",
    deps = [":btlib"],
)

cxx_library(
    name = "btlib",
    srcs = glob(["*.c"], exclude = ["main.c"]),
    exported_headers = glob(["*.h"]),
    visibility = ["PUBLIC"],
)