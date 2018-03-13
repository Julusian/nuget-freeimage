# Updating

1. Build FreeImage targetting vs2015 (possibly from https://github.com/twnkls/FreeImage-3.17.0-VS2015)
1. Both Debug and Release of x64 are required.
1. Copy the contents of Dist/x64 to the Dist folder in this repo.
1. Update the version numbers in nuspec files
1. NuGet.exe pack .\NuGet\native.freeimage.vc140.redist.nuspec
1. NuGet.exe pack .\NuGet\native.freeimage.vc140.nuspec
1. Upload resulting nupkg files