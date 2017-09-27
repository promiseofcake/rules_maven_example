git_repository(
  name = "org_pubref_rules_maven",
  remote = "https://github.com/pubref/rules_maven",
  commit = "43d56ae584ffdf1cd79307728bfd2436c475d35e",
)

load("@org_pubref_rules_maven//maven:rules.bzl", "maven_repositories" ,"maven_repository")
maven_repositories()

maven_repository(
  name = "guice",
  deps = [
    'com.google.inject:guice:4.1.0',
  ],
)
