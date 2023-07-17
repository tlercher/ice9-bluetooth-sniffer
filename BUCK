# A list of available rules and their signatures can be found here: https://buck2.build/docs/api/rules/


# Our actual targets

cxx_binary(
    name = "ice9-bluetooth",
    srcs = glob(["*.c"]),
    headers = glob(["*.h"]),
    link_style = "static",
    deps = [
        '//third_party/libhackrf:libhackrf',
        '//third_party/liquid-dsp:liquid-dsp',
        '//third_party/libbladerf:libbladerf',
        '//third_party/uhd:uhd',
    ],
)