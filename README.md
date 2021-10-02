# Open-Source Projects
OSS is really fun, it gives you freedom, it allows you to learn new things or correct the ideas you thought are right by letting everyone see your works.

Here I'm going to show what I've done and what I'm planning to do in this awesome world of Open-Source.

## [CodeCompanion.Extensions.Dapper.Postgres](https://github.com/kblyr/CodeCompanion.Extensions.Dapper.Postgres)
**SQL Server** has a feature that you can have multiple result set in one procedure call and **Dapper** supported it using **QueryMultiple(...)** method. But **PostgreSQL** doesn't provide this feature but you can create a function that returns **SETOF REFCURSOR**. 

This small and simple library provides a way to mimic the behavior of multiple result set using **REFCURSOR**.

The library has an extension method for **IDbConnection**, the **QueryRefCursors(...)** that will return an instance of **Refcursors** that exposes methods like *Read(...)*, *ReadSingle(...)*, *ReadSingleOrDefault(...)*, *ReadFirst(...)* and *ReadFirstOrDefault(...)* just like what the **Dapper** provides.

See the repository for a code sample.

## [CodeCompanion.FluentSpreadsheet](https://github.com/kblyr/CodeCompanion.FluentSpreadsheet)
This small library provides you a *Fluent API feel* in building spreadsheets in C#. It also abstracts the code from different providers like *EPPlus* and *GemBox.Spreadsheet* so you can change provider without changing all the code.