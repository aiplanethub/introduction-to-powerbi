Data Analysis Expressions (DAX) is a programming language that is used throughout Microsoft Power BI for creating calculated columns, measures, and custom tables. It is a collection of functions, operators, and constants that can be used in a formula, or expression, to calculate and return one or more values. You can use DAX to solve a number of calculations and data analysis problems, which can help you create new information from data that is already in your model.

### Use calculated columns

DAX allows you to augment the data that you bring in from different data sources by creating a calculated column that didn't originally exist in the data source. This feature should be used sparingly, which will be explained later in this module.

For example, assume that you are importing data from a database that contains sales transactions. Each individual sales transaction has the following columns: Order ID, Product ID, Quantity, and Unit Price. Notice that a column doesn't exist for the total sales amount for each order.

The following figure shows how the initial shape of the data appears in a Power BI table visual.
![02-table-visual-ss.png](https://dphi-live.s3.amazonaws.com/media_uploads/02-table-visual-ss_230ea0962ae740089be180f2bc559b78.png)

### Use measures

Calculated columns are useful when you need to operate row by row. However, other situations might require a simpler method. For example, consider a situation wherein you want an aggregation that operates over the entire dataset, and you want the total sales of all rows. Furthermore, you want to slice and dice that data by other criteria like total sales by year, by employee, or by product.

To accomplish those tasks, you would use a measure. You can build a measure without writing DAX code; Power BI will write it for you when you create a quick measure.