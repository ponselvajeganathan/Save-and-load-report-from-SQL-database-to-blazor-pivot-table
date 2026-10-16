# Save and load report from SQL Server Database to a Blazor Pivot Table

## Overview

This sample demonstrates how to persist Syncfusion [Blazor Pivot Table](https://www.syncfusion.com/blazor-components/blazor-pivot-table) reports in a SQL Server database and restore them at runtime. The implementation uses the `Microsoft.Data.SqlClient` package to connect to SQL Server and store Pivot Table report definitions, allowing users to save, load, rename, and manage report configurations across sessions. This approach is useful for enterprise reporting applications that require centralized report storage and consistent layouts for multiple users.

## Key Features

- Uses the Syncfusion Pivot Table report-management functionality to save and retrieve report definitions from SQL Server.
- Integrates `Microsoft.Data.SqlClient` for database connectivity and report persistence.
- Demonstrates runtime loading of previously saved Pivot Table configurations.
- Supports report storage scenarios where layout settings are maintained outside the application.
- Shows how report definitions can be retrieved from a SQL Server database and assigned back to the Pivot Table.
- Demonstrates persistence of Pivot Table settings such as rows, columns, values, filters, formatting, and other report configurations.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework
- SQL Server database
- Microsoft.Data.SqlClient NuGet package

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file located in the `EFPivotTable` project. 
3. Restore all NuGet packages.
4. Set the `EFPivotTable` project as the startup project if required.
5. Configure the SQL Server connection settings used by the sample.
6. Create the required database objects described by the sample implementation.
7. Build the solution.
8. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the `EFPivotTable` project directory.

```bash
dotnet restore
dotnet run
```

5. Ensure the SQL Server connection is configured correctly before running the application.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to report management in Pivot Table, visit https://help.syncfusion.com/grid-sdk/blazor/pivot-table/tool-bar

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
