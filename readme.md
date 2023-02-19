# Youtube Tutorial .net tdd

https://www.youtube.com/watch?v=ULJ3UEezisw

Setup:
- winget install Microsoft.DotNet.SDK.7


History of commands:
- dotnet new sln -o CloudCustomers
- cd CloudCustomers
- dotnet new webapi -o CloudCustomers.API
- dotnet new xunit -o CloudCustomers.UnitTests
- dotnet sln add (ls -r **/*.csproj)
<!-- - dotnet sln add **/*.csproj -->
- cd CloudCustomers.UnitTests
- dotnet add package moq
- dotnet add package fluentassertions

