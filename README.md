# YAML pipeline templates
Templates for CI/CD pipelines


## Note
When using "dotnet-github-nuget-publish-on-release-branch.yml" or "dotnet-github-nuget-publish-on-release.yml" \*.csproj files should not have Version tag as that will conflict with version specified in script.

secrets.PACKAGE_PAT_KEY - This should be specified in repo secrets if you plan to publish to github packages. Its a PAT token with read/write access GitHub to packages.
