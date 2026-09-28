# Binding List Data and Service URLs to the Blazor TreeView

## Overview

This sample demonstrates how to bind data to the Syncfusion [Blazor TreeView](https://www.syncfusion.com/blazor-components/blazor-treeview) component in a Blazor WebAssembly application. The implementation shows two common data-binding approaches: rendering hierarchical records from a local collection and loading TreeView nodes from remote service endpoints. These patterns help developers build navigation systems, file explorers, category structures, and other hierarchical interfaces using both static and dynamic data sources.

## Key Features

- Displays hierarchical data using the Syncfusion TreeView component.
- Demonstrates binding local list data containing parent-child relationships.
- Demonstrates binding TreeView data from remote service URLs.
- Uses Blazor WebAssembly architecture with separate Client, Server, and Shared projects.
- Supports loading node data from API endpoints hosted within the Server project.
- Shows how hierarchical records can be mapped and rendered within the TreeView UI.
- Illustrates service-based data retrieval for dynamic TreeView population.
- Provides sample implementation suitable for category structures, organizational hierarchies, and navigation trees.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `BindingListDataSample.sln`

3. Restore all NuGet packages.
4. Set the startup project 
5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Verify that the TreeView displays hierarchical local data and loads records from service endpoints.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the solution folder.

```bash
cd Binding-List-Data-and-Service-URLs-to-the-Blazor-TreeView
```

4. Restore NuGet packages.

```bash
dotnet restore
```

5. Run the application.

```bash
dotnet run
```

6. Open the application URL displayed in the terminal and verify that the TreeView successfully displays both local and remote data sources.

## Project Structure


`Client/Pages/Index.razor` — hosts the Syncfusion TreeView implementation and demonstrates local list binding and remote service URL binding scenarios.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: https://blazor.syncfusion.com/documentation/treeview/data-binding

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.