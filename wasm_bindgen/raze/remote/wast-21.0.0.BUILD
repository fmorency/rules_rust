"""
@generated
cargo-raze crate build file.

DO NOT EDIT! Replaced on runs of cargo-raze
"""

# buildifier: disable=load
load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_binary",
    "rust_library",
    "rust_test",
)

# buildifier: disable=load
load("@bazel_skylib//lib:selects.bzl", "selects")

package(default_visibility = [
    # Public for visibility by "@raze__crate__version//" targets.
    #
    # Prefer access through "//wasm_bindgen/raze", which limits external
    # visibility to explicit Cargo.toml dependencies.
    "//visibility:public",
])

licenses([
    "notice",  # Apache-2.0 from expression "Apache-2.0"
])

# Generated targets
# Unsupported target "annotations" with type "test" omitted
# Unsupported target "comments" with type "test" omitted
# Unsupported target "parse-fail" with type "test" omitted
# Unsupported target "recursive" with type "test" omitted

# buildifier: leave-alone
rust_library(
    name = "wast",
    crate_type = "lib",
    deps = [
        "@rules_rust_wasm_bindgen__leb128__0_2_4//:leb128",
    ],
    srcs = glob(["**/*.rs"]),
    crate_root = "src/lib.rs",
    edition = "2018",
    rustc_flags = [
        "--cap-lints=allow",
    ],
    version = "21.0.0",
    tags = [
        "cargo-raze",
        "manual",
    ],
    crate_features = [
        "default",
        "wasm-module",
    ],
)
