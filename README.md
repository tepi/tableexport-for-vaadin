# TableExport Add-on for Vaadin 8, for use with the Vaadin 7 compatibility packages

TableExport is a Data Component add-on for the Vaadin 7 compatibility packages of Vaadin 8.

## Overview
* Exporting data to Excel or CSV formats is a common task that comes up time and again. The solution can figured out from various forum posts but it takes a while to put everything together, especially the writing of the Excel file to the browser.
* This add-on takes a Grid or Table as input and exports a decent Excel file containing the data in the Container. It also handles HierarchicalDataProviders / HierarchicalContainers and the resulting Excel file will have the categories and subcategories properly grouped/outlined.
* There are a number of configurable properties. The user can specify a worksheet name, a report title, and an output file name. The user can also specify if there should be a Totals row at the bottom of the export. The user can pass in custom POI CellStyles. However, if none of these are specified, the user only needs to pass in a Grid/Table.
* This add-on requires the Apache POI library (http://poi.apache.org/). 
* This add-on uses Charles Anthony's solution from: http://vaadin.com/forum/-/message_boards/view_message/159583

## License

Add-on is distributed under Apache License 2.0. For license terms, see LICENSE.txt.
