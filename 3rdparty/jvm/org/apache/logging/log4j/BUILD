java_library(
    name = "log4j_api",
    exports = [
        "//external:jar/org/apache/logging/log4j/log4j_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "log4j_core",
    exports = [
        "//external:jar/org/apache/logging/log4j/log4j_core",
        ":log4j_api"
    ],
    visibility = [
        "//visibility:public"
    ]
)


