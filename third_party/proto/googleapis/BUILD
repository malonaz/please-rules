package(default_visibility = ["PUBLIC"])

subinclude("//build_defs:remote")

subinclude("//build_defs/proto:utils")

GOOGLEAPI_REVISION = "5e5d500bc4f8c4d5591cd1fda817556b3fe663a7"

github_proto_library(
    name = "v1alpha1",
    dir = "google/api/expr/v1alpha1",
    files = [
        "checked.proto",
        "eval.proto",
        "explain.proto",
        "syntax.proto",
        "value.proto",
    ],
    repo = "googleapis/googleapis",
    revision = GOOGLEAPI_REVISION,
    deps = [":status"],
)

github_proto_library(
    name = "status",
    dir = "google/rpc",
    files = ["status.proto"],
    repo = "googleapis/googleapis",
    revision = GOOGLEAPI_REVISION,
)
