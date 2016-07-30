public = ["//visibility:public"]

cc_binary(
    name       = "shell",
    srcs       = ["sources/shell.c"],
    deps       = [":sqlite3"],
    visibility = public,
)

cc_library(
    name       = "sqlite3",
    includes   = ["headers"],
    hdrs       = ["headers/sqlite3.h", "headers/sqlite3ext.h"],
    srcs       = ["sources/sqlite3.c"],
    copts      = ["-O2", "-Wall"],
    visibility = public,
)
