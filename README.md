# Blazor DataGrid with Multiple Foreign Key Columns

This sample explains about how to display the multiple columns with foreign key relation in [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

When building data-driven applications, you often need to display related information from other data sources. This sample shows how to configure the Blazor DataGrid to bind multiple columns to the same foreign key data source, enabling you to display different properties from related entities.

The sample includes a working example of an order management interface that displays:

- **Order ID**: Primary key for the order
- **First Name**: Employee first name from a related employee data source
- **Last Name**: Employee last name from the same employee data source  
- **Joined Date**: Order date information

## Features

- **Multiple Foreign Key Columns** - Configure and display multiple related data columns from the same or different data sources in a single grid
- **Unified Data Source Binding** - Bind multiple columns to the same foreign key data source using different display properties
- **Full CRUD Operations** - Add, edit, and delete records while maintaining foreign key relationships and data integrity
- **Real-time Data Updates** - Immediately display changes in foreign key columns as data is modified in the grid
- **Inline Editing** - Edit foreign key column values directly in the grid with automatic validation
- **Responsive Grid Layout** - Seamlessly adapts to different screen sizes with optimized column widths and scrolling

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`MultipleForeignkeyColumn.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-enable-multiple-foreignkey-columns
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/editing#edit-foreign-key-column

**Online example**: https://blazor.syncfusion.com/demos/datagrid/foreign-key-column?theme=fluent2
