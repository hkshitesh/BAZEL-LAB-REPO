load("@rules_java//java:defs.bzl", "java_binary")

package(default_visibility = ["//visibility:public"])

# java_binary(
#     name = "ProjectRunner",
#     srcs = glob(["src/main/java/com/example/*.java"]),
# )

java_binary(
    name = "ProjectRunner",
    srcs = ["src/main/java/com/example/ProjectRunner.java"],
    main_class = "com.example.ProjectRunner",
    deps = [":greeter"],
)

java_library(
    name = "greeter",
    srcs = ["src/main/java/com/example/Greeting.java"],
    visibility = ["//src/main/java/com/example/cmdline:__pkg__"],
)
