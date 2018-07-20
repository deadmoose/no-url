This is generated with https://github.com/johnynek/bazel-deps/commit/13bef5b78a9fb8ea508ce5f0d43fee8295921a1f

Using:

`../bazel-deps/gen_maven_deps.sh generate -r `pwd` -s 3rdparty/workspace.bzl -d dependencies.yaml`

Looking in the generated 3rdparty/workspace.bzl, the elements returned by `list_dependencies()` have
`sha1` rather than the expected `sha256`, and no `url`.
