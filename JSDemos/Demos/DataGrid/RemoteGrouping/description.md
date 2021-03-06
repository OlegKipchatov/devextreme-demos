Remote (server-side) operations can boost the **DataGrid**'s performance on large datasets. In this demo, the **DataGrid** works with a million records seamlessly because they are processed on the server.

To notify the **DataGrid** that it works with a pre-processed dataset, set the [remoteOperations](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/remoteOperations/) option to **true**.

You can also specify options that allow the widget to load data on demand to reduce the amount of transmitted data. Set the **grouping**.[autoExpandAll](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/grouping/#autoExpandAll) option to **false** to collapse all the groups at startup. Data for each group is loaded only when the user expands the group. Enable the *"virtual"* **scrolling**.[mode](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/scrolling/#mode) to load only those records that come into the viewport when the grid is scrolled vertically.

The **DataGrid** communicates with the server according to a protocol. Refer to the [Load Data](/Documentation/Guide/Widgets/DataGrid/Data_Binding/Custom_Sources/#Load_Data) article for information on it.