# 0.2.1

- Added dart_source_cleanup option (#51)
- Upgraded dependencies

# 0.2.0

- Breaking changes: upgraded to build_runner 1.0.0, build_modules 0.4.0

# 0.1.12

- Fixed function responsible for resolving module paths for dartdevc to support symlinked
  entrypoints.

# 0.1.11

- Upgraded to latest build_runner (fixes dependency resolution with Dart 2 stable).

# 0.1.10

- Handle entrypoints inside `lib/` folder.

# 0.1.9

- Fixed analysis warnings with latest Pub and Dart SDK.

# 0.1.8

- Fixed strong mode issue with parsing dart2js_args using latest Dart 2 SDK.

# 0.1.7

- Removed extra dependency constraint on analyzer package.
- Upgraded all dependencies to latest.

# 0.1.6

- Removed redundant `**_test.dart` glob from build config which was causing
  issues when build_node_compilers used together with build_web_compilers.

# 0.1.5

- Expand support for package:build_config to include version 0.3.x.

# 0.1.4

- Fixed deprecation warnings with latest Dart 2 dev SDK.

# 0.1.3

- Remove extra dependencies in build_node_compilers (#22)

# 0.1.2

- Upgraded dependencies to match with latest version of build_web_compilers.

# 0.1.1

- Create `.packages` file and use the new frontend with `dart2js`.

# 0.1.0+1

- Use `--use-old-frontend` with `dart2js` as a stopgap until we can add support
  for `.packages` files.
- Fixed deprecation warnings.

# 0.1.0

- Initial version based on `build_web_compilers`.
