# C# Mentoring Plan

Last revised: 2022 Feb (see commit history for more detail)


## Prerequisites

A fairly modern macOS or Linux computer.

Some C#, Java, C++, _or_ D experience, otherwise the language & programming concepts will be a bit too unfamiliar.

Some familiarity with the commandline will be helpful.

## Getting started with Dotnet 6

We will code the main backbone of this application using **dotnet 6** (.NET 6), the latest (as of 2022 Feb) version of Dotnet, Microsoft's main software development kit. Specifically, we will be using the **ASP.NET framework** and related software libraries.

This is the dotnet homepage:

- https://dotnet.microsoft.com/en-us/

This is a tutorial you can follow to install dotnet and test that it works:

- https://dotnet.microsoft.com/en-us/learn/dotnet/hello-world-tutorial/intro

Once you have installed dotnet, you should continue the tutorial, just to test that everything is working and you have a basic understanding of how you can use it.

Don't worry if it seems irrelevant to you - you shouldn't be here for much longer than 5 minutes, and you don't need to study things in depth here, as you can always come back in the near future if you forget something.

> **Why is it called dotnet or .NET?**
> 
> Because dotnet is the name of the command we run,
> and because it's easier to type fluently than .NET,
> and it's also easier to search "on the net" for "dotnet" than ".NET"!

> **Why dotnet 6?**
> 
> Because dotnet 6 has a number of improvements to dotnet 5,
> which will help ease strangers to C# in.
> We're also past the era of ".NET Core" and ".NET Framework" confusion.
> I also really like [file scoped namespaces](https://devblogs.microsoft.com/dotnet/announcing-net-6/#file-scoped-namespaces).

> **Why dotnet at all?**
> 
> Because Microsoft has really good documentation for getting started with ASP.NET,
> because there's job opportunities to motivate learners,
> and because I feel it's almost easier to get started with dotnet on many different
> computers than Java.
> 
> BUT I also think C# is close enough to Java in that it offers a good learning experience
> for business programming. Later, someone might want to get familiar with the JavaScript ecosystem,
> which is much more decentralised and less strict, but also has a lot of job opportunities as well.
> 
> Finally, unlike the Java ecosystem, the .NET ecosystem is growing quite fast, so it gives
> beginners an example of the churn in the tech industry, without being as dramatic as Python or JavaScript.
> You can even see [roadmaps](https://themesof.net/roadmap?product=.NET&release=7.0).

## Getting started with ASP .NET

The next step is to show you how you can get started with an ASP.NET project.

Follow this tutorial to start an ASP.NET project.

- https://docs.microsoft.com/en-us/aspnet/core/getting-started/?view=aspnetcore-6.0&tabs=macos

## FUTURE (TODO)

- Formulating a personal project plan.
- Frontend to database and everything in between.
- Operational security (e.g. don't commit secrets, identifying information, EXIF metadata on image assets, etc.
- Library usage, and licensing concerns.
- Mocking up a database, and gradually moving to multiple dev/production environments then to Supabase.
- Deploying a docker application.
- The nitty gritty getting this publically accessible.

Please be patient as I continue to add detail to this plan.
