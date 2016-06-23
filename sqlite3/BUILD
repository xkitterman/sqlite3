cc_binary(
    name       = "sql",
    srcs       = ["src/shell.c"],
    deps       = [":sqlite3"],
    visibility = ["//visibility:public"],
)

cc_library(
    name       = "sqlite3",
    includes   = ["inc"],
    hdrs       = ["inc/sqlite3.h", "inc/sqlite3ext.h"],
    srcs       = ["src/sqlite3.c"],
    copts      = ["-O2", "-Wall"],
    visibility = ["//visibility:public"],
)
