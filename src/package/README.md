# Template

[Original source](https://docs.microsoft.com/en-us/dotnet/core/tutorials/create-custom-template)

Once the template is installed on your local machine, it will allow you to generate consistent projects.

---

### Install Template

> Assuming the repository is downloaded to `c:\source`

**Usage:**
```csharp
dotnet new -i c:\source\template-pkg\src\template.package
```

---

### Run Template

The following example will create copy of the `package.template` project named `MyNewProject` and locate it to a folder called `NewProject\src` which is relatively located to the working directory.

**Usage:**
```csharp
dotnet new package.template -n [Project Title] -o [Location]
```
**Example:**
```csharp
dotnet new package.template -n MyNewProject -o NewProject/src
```
---
