## What Is This?

This is an example repo corresponding to multiple lessons within the LearnHowToProgram.com walkthrough on creating an ASP.NET Core MVC client to query a custom [ASP.NET Core API](https://github.com/epicodus-lessons/section-6-cretaceous-park-api-csharp-net6) in [Section 6: Building an API](https://www.learnhowtoprogram.com/c-and-net/building-an-api).

This project is called the "Cretaceous Park Client", while the API is called the "Cretaceous Park API".

This project (the Cretaceous Park Client) corresponds to the following classwork on LearnHowToProgram.com:

- https://www.learnhowtoprogram.com/c-and-net/building-an-api/mvc-client-getall
- https://www.learnhowtoprogram.com/c-and-net/building-an-api/mvc-client-getdetails
- https://www.learnhowtoprogram.com/c-and-net/building-an-api/mvc-client-post-put-and-delete

Finally, this project was scaffolded using [`dotnet new`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new).

## How To Run This Project

### Install Tools

Install the tools that are introduced in [this series of lessons on LearnHowToProgram.com](https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c).

### Set Up and Run the Cretaceous Park API Project

First, following the instructions in the README of [this repo](https://github.com/epicodus-lessons/section-6-cretaceous-park-api-csharp-net6) to set up and run the Cretaceous Park API.

### Set Up and Run This Project

1. Clone this repo.
2. Open the terminal and navigate to this project's production directory called "CretaceousClient".
3. Within the production directory "CretaceousClient", run `dotnet watch run` in the command line to start the project in development mode with a watcher.
4. Open the browser to _https://localhost:7277/_. If you cannot access https://localhost:7277 it is likely because you have not configured a .NET developer security certificate for HTTPS. To learn about this, review this lesson: [Redirecting to HTTPS and Issuing a Security Certificate](https://www.learnhowtoprogram.com/lessons/redirecting-to-https-and-issuing-a-security-certificate).
