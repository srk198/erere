# CoreLoggingTests
this branch is about learning abvout learning branch

Support files for the blog post : [Logging in a .Net Core Library](https://xfischer.github.io/logging-dotnet-core/)

**A simple test solution with :**
- A library emiting logs with ILogger from *Microsoft.Extensions.Logging.Abstractions*
- A console app referencing the library and setting up filtered listeners using Dependency Injection

**Conclusion :**
- You can setup logging in a library without forcing a concrete logging implementation.
- It's up to the app referencing your library to choose whether to listen to traces and to choose among well known providers (NLog, Serilog, ...)

**Sources :**
- [Logging in ASP.NET Core](https://docs.microsoft.com/aspnet/core/fundamentals/logging/?view=aspnetcore-2.)

**Used frameworks**
- .Net Standard 2.1
- .Net Framework 4.6.1
- .Net Core 3.1
