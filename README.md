# Blazor DataGrid Lazy Load Grouping

## Overview

This sample demonstrates the Lazy Load Grouping feature in the Syncfusion Blazor DataGrid. Lazy load grouping improves performance when working with large grouped datasets by initially rendering only group caption rows and loading the corresponding child records when a group is expanded. This approach minimizes data processing, reduces memory consumption, and improves responsiveness compared to loading all grouped records at once.

## Key Features

- Demonstrates the Syncfusion Blazor DataGrid lazy load grouping functionality.
- Uses DataGrid grouping to organize records into expandable group sections.
- Loads grouped child records only when a user expands a group caption row.
- Reduces initial rendering overhead by displaying collapsed group captions during the initial load.
- Optimizes large dataset presentation by deferring the loading of nested group content.
- Provides a practical example of improving DataGrid scalability through on-demand data loading.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `LazyLoadGroup.sln`.
3. Restore all NuGet packages.
4. Set the `LazyLoadGroup` project as the startup project if required.
5. Build the solution.
6. Run the project using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts. The repository README references `https://localhost:5001` as the sample URL.

## Project Structure

- `Pages/` — contains the Razor pages that host and render the Syncfusion DataGrid lazy load grouping sample.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Lazy Load Grouping documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/lazy-load-grouping

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.