android_library(
    name = "lib",
    srcs = glob(["src/main/java/**/*.java"]),
    custom_package = "com.xtbc.ui",
    manifest = "src/main/AndroidManifest.xml",
    resource_files = glob(["src/main/res/**"], exclude=["src/main/res/.DS_Store"]),
    deps = [
        "@androidsdk//com.android.support:appcompat-v7-24.0.0"
    ]
)
