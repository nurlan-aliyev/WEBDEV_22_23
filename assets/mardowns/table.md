
# HTML  Tables

HTML tables allow web developers to arrange data into rows and columns.

## Example
<table>  
<tr>  
<th>Company</th>  
<th>Contact</th>  
<th>Country</th>  
</tr>  
<tr>  
<td>Alfreds Futterkiste</td>  
<td>Maria Anders</td>  
<td>Germany</td>  
</tr>  
<tr>  
<td>Centro comercial Moctezuma</td>  
<td>Francisco Chang</td>  
<td>Mexico</td>  
</tr>  
</table>

## Define an HTML Table

A table in HTML consists of table cells inside rows and columns.

### Example

A simple HTML table:
```
<table>  
<tr>  
<th>Company</th>  
<th>Contact</th>  
<th>Country</th>  
</tr>  
<tr>  
<td>Alfreds Futterkiste</td>  
<td>Maria Anders</td>  
<td>Germany</td>  
</tr>  
<tr>  
<td>Centro comercial Moctezuma</td>  
<td>Francisco Chang</td>  
<td>Mexico</td>  
</tr>  
</table>
```


## Table Cells

Each table cell is defined by a  `<td>`  and a  `</td>`  tag.

`td`  stands for table data.

Everything between  `<td>`  and  `</td>`  are the content of the table cell.

### Example
```
<table>  
<tr>  
<td>Annushka</td>  
<td>Karina</td>  
<td>Dima</td>  
</tr>  
</table>
```

**Note:**  A table cell can contain all sorts of HTML elements: text, images, lists, links, other tables, etc.


## Table Rows

Each table row starts with a  `<tr>`  and ends with a  `</tr>`  tag.

`tr`  stands for table row.

### Example
```
<table>  
<tr>  
<td>Ukraine</td>  
<td>Germany</td>  
<td>Hungary</td>  
</tr>  
<tr>  
<td>+380</td>  
<td>+49</td>  
<td>+36</td>  
</tr>  
</table>
```

You can have as many rows as you like in a table; just make sure that the number of cells are the same in each row.

**Note:**  There are times when a row can have less or more cells than another. You will learn about that in a later chapter.

----------

## Table Headers

Sometimes you want your cells to be table header cells. In those cases use the  `<th>`  tag instead of the  `<td>`  tag:

`th`  stands for table header.

### Example

Let the first row be table header cells:
```
<table>  
<tr>  
<th>Person 1</th>  
<th>Person 2</th>  
<th>Person 3</th>  
</tr>  
<tr>  
<td>Annushka</td>  
<td>Karina</td>  
<td>Dima</td>  
</tr>  
<tr>  
<td>100</td>  
<td>100</td>  
<td>100</td>  
</tr>  
</table>
```


By default, the text in  `<th>`  elements are bold and centered, but you can change that with CSS.

## HTML Table Tags

<table>  
<tr>  
<th>Tag</th>  
<th>Description</th>
</tr>  
<tr>  
<td>< table ></td>  
<td>Defines a table</td>  
</tr>  
<tr>  
<td>< th ></td>  
<td>Defines a header cell in a table</td>  
</tr>  
<tr>  
<td>< tr ></td>  
<td>Defines a row in a table</td>  
</tr>  
<tr>  
<td>< td ></td>  
<td>Defines a cell in a table</td>  
</tr>  
<tr>  
<td>< caption ></td>  
<td>Defines a table caption</td>  
</tr>
<tr>  
<td>< colgroup ></td>  
<td>Specifies a group of one or more columns in a table for formatting</td>  
</tr>  
<tr>  
<td>< col ></td>  
<td>Specifies column properties for each column within a < <b>colgroup</b> > element</td>  
</tr>   
<tr>  
<td>< thead ></td>  
<td>Groups the header content in a table</td>  
</tr>  
<tr>  
<td>< tbody ></td>  
<td>Groups the body content in a table</td>  
</tr>  
<tr>  
<td>< tfoot ></td>  
<td>Groups the footer content in a table</td>  
</tr>    
</table>
