# json-grid-viewer
This extension allows you get a better overview of the content in a JSON file by showing it in a resizable grid.
- Columns are resizable.
- Each object and array is collapsed by default but can be expanded to see all contents
- Arrays of objects show in a table format

## Demo
![demo](./demo.webp)

## Usage
To open a json file in the grid viewer, right click the file, select *Open With... > JSON Grid*. The grid is read only but will display any changes made to the json file live, provided the json is valid.

## To do:
- Add editing capabilities
- Take colours from the active theme

## ChangeLog
- 0.1.1 change white blank style in data table, to show `\n` correctly.