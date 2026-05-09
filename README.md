# CI-Demo

An old demo repository created in October 2017 to experiment with continuous
integration setup. It is not an active project and contains no application
source code.

## Contents

- `azure-pipelines.yml` - An Azure Pipelines build definition (added 2021-01-19)
  targeting an ASP.NET Core / .NET Framework solution. It uses the
  `windows-latest` pool, .NET Core SDK 3.1.201, and runs restore, build, and
  publish steps for any `*.csproj` in the repo (test step is disabled). Note
  that no `.sln` or `.csproj` files are actually committed, so the pipeline
  has nothing to build as-is.
- `.gitignore` - Standard Visual Studio gitignore.

## Status

Archived / inactive. Kept for historical reference only.
