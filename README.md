# Introduction

![NuGet Version](https://img.shields.io/nuget/v/Qrtix.EFCore.Converters?logo=nuget&label=EFCore.Converters)
![NuGet Version](https://img.shields.io/nuget/v/Qrtix.EFCore.RepositoryPattern?style=flat&logo=nuget&label=EFCore.RepositoryPattern)
![GitHub Repo stars](https://img.shields.io/github/stars/carlosjortiz/EFCore?style=flat&logo=github)


Welcome to the documentation for EFCore libraries! This documentation serves as a comprehensive guide to using these
libraries effectively in your .NET projects. Whether you're a beginner looking to get started with `EFCore.Converters` or
an experienced developer seeking to streamline database operations with `EFCore.RepositoryPattern`, you'll find everything
you need to know right here.

Consult the online [documentation](https://carlosjortiz.github.io/EFCore/) for more details.

- [About EFCore.Converters](#about-efcoreconverters)
- [About EFCore.RepositoryPattern](#about-efcorerepositorypattern)
- [What You'll Find in This Documentation](#what-youll-find-in-this-documentation)
- [Contributing](#contributing)

## About `EFCore.Converters`

`EFCore.Converters` is a library designed to simplify the process of working with complex data types when using Entity
Framework Core (EF Core). It provides a set of custom value converters that allow you to map .NET types to database
columns, facilitating seamless storage and retrieval of data in your EF Core applications. With `EFCore.Converters`, you
can easily handle scenarios involving enums, JSON data, spatial data types, and more, making your database interactions
more efficient and intuitive.

[EFCore.Converters README](src/EFCore.Converters/README.md)

## About `EFCore.RepositoryPattern`

`EFCore.RepositoryPattern` is a library that implements the repository pattern on top of Entity Framework Core (EF Core),
providing a structured approach to database access and management. By decoupling your application's data access logic
from the underlying data source, `EFCore.RepositoryPattern` promotes modularity, testability, and maintainability. With
this library, you can create and use repositories to perform CRUD (Create, Read, Update, Delete) operations, manage
transactions, and execute custom queries, all while adhering to best practices in software architecture.

[EFCore.RepositoryPattern README](src/EFCore.RepositoryPattern/README.md)

## What You'll Find in This Documentation

In this documentation, you'll discover detailed explanations, code samples, and practical tutorials covering various
aspects of `EFCore.Converters` and `EFCore.RepositoryPattern`. Here's what you can expect to find:

- **Installation Guide:** Learn how to install and configure the libraries in your .NET projects.
- **Core Concepts:** Understand the fundamental concepts and principles behind `EFCore.Converters` and
  `EFCore.RepositoryPattern`.
- **Getting Started:** Get up and running quickly with step-by-step instructions for basic usage.
- **Advanced Usage and Tutorials:** Dive deeper into advanced features and scenarios, with hands-on tutorials and
  examples.
- **API Reference:** Explore the complete API documentation for both libraries, including classes, methods, and
  properties.
- **Best Practices:** Discover best practices, tips, and recommendations for optimizing your usage of `EFCore.Converters`
  and `EFCore.RepositoryPattern`.

Whether you're building a small application or a large-scale enterprise system, `EFCore.Converters` and
`EFCore.RepositoryPattern` are powerful tools that can help you achieve your goals efficiently and effectively. Let's dive
in and explore the capabilities of these libraries together!

## Contributing

**Did you find a bug?**

- Ensure the bug was not already reported by searching on GitHub
  under [Issues](https://github.com/carlosjortiz/EFCore/issues).
- If you're unable to find an open issue addressing the
  problem, [open a new one](https://github.com/carlosjortiz/EFCore/issues/new). Be sure to include a title and clear
  description, as much relevant information as possible, and a code sample or an executable test case demonstrating the
  expected behavior that is not occurring.

**Did you write a patch that fixes a bug?**

- Open a new GitHub pull request with the patch.
- Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

**Do you intend to add a new feature or change an existing one?**

- First suggest your change in the [EFCore ideas page](https://github.com/carlosjortiz/EFCore/discussions/categories/ideas)
  for discussion.
- There are no fixed rules on what should and shouldn't be in this library, but some features are more valuable than
  others, and some require long-term maintenance that outweighs the value of the feature. So please get sign-off from
  the
  project leader (Carlos J. Ortiz) before putting in an excessive amount of work.

**Do you have questions about the source code?**

- Ask any question about how to use EFCore in
  the [EFCore discussion page](https://github.com/carlosjortiz/EFCore/discussions/new?category=q-a).


If you have any questions or need further assistance, don't hesitate to reach out to us.

Happy coding!