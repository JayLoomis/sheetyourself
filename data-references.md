# Referencing Data

Almost everything you do in Sheets references data. Here's how to do it.

## Terminology

<dl>
  <dt>Cell</dt>
  <dd>A single cell in the spreadsheet. Can contain a value or a formula.</dd>
  
  <dt>Range</dt>
  <dd>A collection of contiguous cells. May cross both rows and columns, but must
    be rectagular. A cell is a range by definition.</dd>
  
  <dt>Relative reference</dt>
  <dd>A reference to a range that is interpreted to be relative to the cell in
    which the formula is stored. For single references, the results are the same
    as for an absolute reference, but if you copy the formula to another cell, it
    will adjust the cell reference to match the relative position.</dd>
  
  <dt>Absolute reference</dt>
  <dd>A reference to a specific range that will not adjust if copied to another
    cell.</dd>
  
  <dt>Sheet</dt>
  <dd>A discrete range of cells within the larger spreadsheet document. Different
    sheets are named, and are displayed in tabs along the bottom of the data view
    in the app.</dd>
</dl>
  
## Reference basics

Relative references on the same sheet:

-   Reference a cell with the letter of its column followed by the number of its
    row: `C12`
-   Reference a range with a reference to one corner, a colon, and a reference to
    the opposite corner: `B6:E14`
-   Convention dictates that you reference a range with the top left corner
    followed by the bottom right, but in most cases, it doesn't matter which
    corners and in what order.
-   When entering a formula, you can click on a cell to insert a relative
    reference to it in the formula at the cursor. You can insert a range by
    clicking and dragging to select the cells in the range.    
    
Absolute references on the same sheet:

-   Make a row, column, or both absolute by placing a dollar sign before the
    letter or number: `$B4`, `S$33`, `$H$1`
-   Hold **F4** while clicking on a cell to get it's absolute reference.

References to different sheets:

-   You can reference data on a different sheet by putting the sheet name, followed by an exclamation point in front of the reference: `clients!A2:B52`
<!--
----5----10---15---20---25---30---35---40---45---50---55---60---65---70---75---80
-->
