To Reproduce [Source Generator works with dotnet cli but fails with TypeLoadException in VS](https://github.com/dotnet/runtime/issues/107926)

- Clone this repo
- Open it in VS
- Compile and Run inside VS by hitting control + F5

## Output
```bash
Build started at 9:24 AM...
1>------ Build started: Project: SourceGen, Configuration: Debug Any CPU ------
1>CSC : warning CS8784: Generator 'SdkGenerator' failed to initialize. It will not contribute to the output and compilation errors may occur as a result. Exception was of type 'TypeLoadException' with message 'Could not load type 'AutoSDK.Models.ModelData' from assembly 'AutoSDK, Version=0.0.0.0, Culture=neutral, PublicKeyToken=603f13207e65c17b'.'.
1>SourceGen -> C:\Users\xiaoyuz\source\repos\SourceGen\bin\Debug\net8.0\SourceGen.dll
1>Done building project "SourceGen.csproj".
```
