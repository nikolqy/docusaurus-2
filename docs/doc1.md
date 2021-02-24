---
id: doc1
title: Hello World
sidebar_label: Hello World
---

# Get started with .NET

This article teaches you how to create and run a "Hello World!" .NET app.

If you're unsure what .NET is, start with the [.NET introduction](introduction.md).

## Create an application

First, download and install the [.NET SDK](https://dotnet.microsoft.com/download/dotnet-core) on your computer.

Next, open a terminal such as **PowerShell**, **Command Prompt**, or **bash**. Enter the following `dotnet` commands to create and run a C# application:

```dotnetcli
dotnet new console --output sample1
dotnet run --project sample1
```

You see the following output:

```output
Hello World!
```

Congratulations! You've created a simple .NET application.

## Next steps

Get started developing .NET applications by following a [step-by-step tutorial](../standard/get-started.md) or by watching [.NET 101 videos](https://www.youtube.com/playlist?list=PLdo4fOcmZ0oWoazjhXQzBKMrFuArxpW80) on YouTube.
