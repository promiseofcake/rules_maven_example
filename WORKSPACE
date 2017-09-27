git_repository(
  name = "org_pubref_rules_maven",
  remote = "https://github.com/pubref/rules_maven",
  commit = "43d56ae584ffdf1cd79307728bfd2436c475d35e",
)

load("@org_pubref_rules_maven//maven:rules.bzl", "maven_repositories" ,"maven_repository")
maven_repositories()

maven_repository(
    name = 'guice',
    deps = [
        'com.google.inject:guice:4.1.0',
    ],
    transitive_deps = [
        '0235ba8b489512805ac13a8f9ea77a1ca5ebe3e8:aopalliance:aopalliance:1.0',
        '6ce200f6b23222af3d8abb6b6459e6c44f4bb0e9:com.google.guava:guava:19.0',
        'eeb69005da379a10071aa4948c48d89250febb07:com.google.inject:guice:4.1.0',
        '6975da39a7040257bd51d21a231b76c915872d38:javax.inject:javax.inject:1',
    ],
)
load("@guice//:rules.bzl", "guice_compile")
guice_compile()
