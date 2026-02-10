# Virtual ADGV

**Virtual ADGV (Virtual Advanced DataGridView)** is an enhanced fork of the original **[Advanced DataGridView](https://github.com/davidegironi/advanceddatagridview)**. It is a .NET WinForms **DataGridView with advanced Filtering and Sorting** capabilities, now updated with dedicated support for **Virtual Mode** and fixes for modern .NET environments.

## Download

* **[NuGet (VirtualADGV)](https://www.nuget.org/packages/VirtualADGV)**
* **[GitHub Repository](https://github.com/HibrahimBoz/VirtualAdvanceddatagridview)**
* **[Latest Release](https://github.com/HibrahimBoz/VirtualAdvanceddatagridview/releases/latest)**

## Key Features & Improvements

* **[NEW] Virtual Mode Support**: Specifically optimized to handle large datasets (millions of rows) efficiently using DataGridView's Virtual Mode.
* **[FIX] Modern .NET Resource Loading**: Resolved the `MissingManifestResourceException` commonly encountered in .NET 5, 6, 7, and 8 environments.
* **Advanced Filtering & Sorting**: Retains the powerful Excel-like filtering and multi-column sorting from the original ADGV.
* **Cross-Platform Compatibility**: Supports .NET 5.0, 6.0, 7.0, and 8.0 Windows environments.

## Requirements

* Microsoft Windows with .NET 5, 6, 7, 8 or later.

## Usage (Virtual Mode)

To use Virtual Mode with VirtualADGV, ensure you handle the `CellValueNeeded` event and set the `VirtualMode` property to `true`. This fork ensures that icons and filter menus load correctly even when the grid is in virtual mode.

## Development & Fork Info

This project is a fork maintained by **Halil İbrahim Bozoğlu**. It aims to provide critical fixes and performance features for high-performance data analytics applications.

Original work by **Davide Gironi** and **Zuby**.

## License

Copyright (c) Davide Gironi, 2015  
Modified work Copyright (c) 2026 Halil İbrahim Bozoğlu  
Virtual ADGV is open source software licensed under the [Microsoft Public License (Ms-PL) license](http://opensource.org/licenses/MS-PL)  
Original work Copyright (c), 2013 Zuby <zuby@me.com> http://adgv.codeplex.com