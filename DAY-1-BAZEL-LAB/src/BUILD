load("@rules_java//java:defs.bzl","java_binary")

# java_binary(
#     name ="HelloTarget",
#     srcs =["Hello.java","Greeting.java"],
#     main_class = "Hello"
# )

java_binary(
    name ="HelloTarget",
    srcs =["Hello.java"],
    main_class = "Hello",
    deps = [":greeter"],
)

java_library(
    name = "greeter",
    srcs = ["Greeting.java"]
)