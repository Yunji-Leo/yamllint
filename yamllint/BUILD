py_binary(
    name = "__main__",
    srcs = ["__main__.py"],
    deps = [
        ":lib",
    ]
)

py_library(
    name = "lib",
    srcs = [
        "__init__.py",
        "cli.py",
        "config.py",
        "linter.py",
        "parser.py",
    ],
    data = [
        "//yamllint/conf:conf",
    ],
    deps = [
        "//yamllint/rules:lib",
    ]
)