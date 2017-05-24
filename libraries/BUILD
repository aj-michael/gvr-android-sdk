package(default_visibility = ["//visibility:public"])

aar_import(
    name = "sdk-audio",
    aar = "sdk-audio-1.60.0.aar",
    exports = [
        ":sdk-base",
    ],
)

aar_import(
    name = "sdk-base",
    aar = "sdk-base-1.60.0.aar",
    exports = [
        ":sdk-common",
    ],
)

aar_import(
    name = "sdk-common",
    aar = "sdk-common-1.60.0.aar",
    exports = [
        "@protobuf_javanano//jar",
    ],
)
