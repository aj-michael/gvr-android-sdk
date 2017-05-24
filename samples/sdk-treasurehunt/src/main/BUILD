android_binary(
    name = "app",
    srcs = glob(["java/com/google/vr/sdk/samples/treasurehunt/*.java"]),
    manifest = "AndroidManifest.xml",
    resource_files = glob(["res/**"]),
    custom_package = "com.google.vr.sdk.samples.treasurehunt",
    deps = [
        "//libraries:sdk-audio",
        "//libraries:sdk-base",
    ],
)
