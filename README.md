# Open-Source Projects
OSS is really fun, it gives you freedom, it allows you to learn new things or correct the ideas you thought are right by letting everyone see your works.

Here I'm going to show you what I've done and what I'm planning to do in this awesome world of Open-Source.
<br><br><br>





## CodeCompanion.*
Every repository that is prefixed with *CodeCompanion* is a simple and small library that commonly used in a project.
<br><br><br>





### CodeCompanion.EntityFrameworkCore
[![GitHub](https://img.shields.io/github/license/kblyr/CodeCompanion.EntityFrameworkCore)](https://raw.githubusercontent.com/kblyr/CodeCompanion.EntityFrameworkCore/main/LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kblyr/CodeCompanion.EntityFrameworkCore?color=white&logo=github)](https://github.com/kblyr/CodeCompanion.EntityFrameworkCore)
[![Nuget version (CodeCompanion.EntityFrameworkCore)](https://img.shields.io/nuget/v/CodeCompanion.EntityFrameworkCore?logo=nuget)](https://www.nuget.org/packages/CodeCompanion.EntityFrameworkCore)

This simple library exposes commonly used patterns when using Entity Framework Core.
<br><br><br>





### CodeCompanion.Exceptions
[![GitHub](https://img.shields.io/github/license/kblyr/CodeCompanion.Exceptions)](https://raw.githubusercontent.com/kblyr/CodeCompanion.Exceptions/main/LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kblyr/CodeCompanion.Exceptions?color=white&logo=github)](https://github.com/kblyr/CodeCompanion.Exceptions)
[![Nuget version (CodeCompanion.Exceptions)](https://img.shields.io/nuget/v/CodeCompanion.Exceptions?logo=nuget)](https://www.nuget.org/packages/CodeCompanion.Exceptions)

A small library that exposes general-purposes and supplementary exception classes
<br><br><br>





### CodeCompanion.Extensions.Dapper.Postgres
[![GitHub](https://img.shields.io/github/license/kblyr/CodeCompanion.Extensions.Dapper.Postgres)](https://raw.githubusercontent.com/kblyr/CodeCompanion.Extensions.Dapper.Postgres/main/LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kblyr/CodeCompanion.Extensions.Dapper.Postgres?color=white&logo=github)](https://github.com/kblyr/CodeCompanion.Extensions.Dapper.Postgres)
[![Nuget version (CodeCompanion.Extensions.Dapper.Postgres)](https://img.shields.io/nuget/v/CodeCompanion.Extensions.Dapper.Postgres?logo=nuget)](https://www.nuget.org/packages/CodeCompanion.Extensions.Dapper.Postgres)

**SQL Server** has a feature that you can have multiple result set in one procedure call and **Dapper** supported it using **QueryMultiple(...)** method. But **PostgreSQL** doesn't provide this feature but you can create a function that returns **SETOF REFCURSOR**. 

This small and simple library provides a way to mimic the behavior of multiple result set using **REFCURSOR**.

The library has an extension method for **IDbConnection**, the **QueryRefCursors(...)** that will return an instance of **Refcursors** that exposes methods like *Read(...)*, *ReadSingle(...)*, *ReadSingleOrDefault(...)*, *ReadFirst(...)* and *ReadFirstOrDefault(...)* just like what the **Dapper** provides.

See the repository for a code sample.
<br><br><br>





### CodeCompanion.FluentEnumerable
[![GitHub](https://img.shields.io/github/license/kblyr/CodeCompanion.FluentEnumerable)](https://raw.githubusercontent.com/kblyr/CodeCompanion.FluentEnumerable/main/LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kblyr/CodeCompanion.FluentEnumerable?color=white&logo=github)](https://github.com/kblyr/CodeCompanion.FluentEnumerable)
[![Nuget version (CodeCompanion.FluentEnumerable)](https://img.shields.io/nuget/v/CodeCompanion.FluentEnumerable?logo=nuget)](https://www.nuget.org/packages/CodeCompanion.FluentEnumerable)

A small library that provides extension methods to use the Fluent API pattern.
<br><br><br>





### CodeCompanion.FluentSpreadsheet
[![GitHub](https://img.shields.io/github/license/kblyr/CodeCompanion.FluentSpreadsheet)](https://raw.githubusercontent.com/kblyr/CodeCompanion.FluentSpreadsheet/main/LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kblyr/CodeCompanion.FluentSpreadsheet?color=white&logo=github)](https://github.com/kblyr/CodeCompanion.FluentSpreadsheet)
[![Nuget version (CodeCompanion.FluentSpreadsheet)](https://img.shields.io/nuget/v/CodeCompanion.FluentSpreadsheet?logo=nuget)](https://www.nuget.org/packages/CodeCompanion.FluentSpreadsheet)

This small library provides you a *Fluent API feel* in building spreadsheets in C#. It also abstracts the code from different providers like *EPPlus* and *GemBox.Spreadsheet* so you can change provider without changing all the code.
<br><br><br>





### CodeCompanion.Processes
[![GitHub](https://img.shields.io/github/license/kblyr/CodeCompanion.Processes)](https://raw.githubusercontent.com/kblyr/CodeCompanion.Processes/main/LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kblyr/CodeCompanion.Processes?color=white&logo=github)](https://github.com/kblyr/CodeCompanion.Processes)
[![Nuget version (CodeCompanion.Processes)](https://img.shields.io/nuget/v/CodeCompanion.Processes?logo=nuget)](https://www.nuget.org/packages/CodeCompanion.Processes)

This small library provides interfaces for executing processes
