## Nested Arrays: Tic-tac-toe and a Table again

Arrays are useful structures for storing collections of data: lists of numbers, strings, etc. They are fairly simple and their flexibility leads to unlimited possibilities for their use. This assignment deals with *Nested Arrays*. Arrays whose elements are arrays. In other words, arrays of arrays.

### Release 0. Creating a field for a game Tic-tac-toe.

```javascript
generateTicTacToe()
// => [["X", "O", "X"], ["O", "O", "X"], ["X", "X", "O"]
generateTicTacToe()
// => [["O", "O", "X"], ["X", "X", "O"], ["O", "O", "X"]]
```
*Figure 1*. Generating tic-tac-toe.

You need to write a method `generateTicTacToe` that returns a nested array representing a tic-tac-toe board. The board must be filled with X (crosses) and 0 (zeros). You can decide how realistic the board will be (e.g. four X letters and five 0s (i.e. there can't be 2 more zeros than crosses), only one winner, etc.). The only rule is that the board must be completely filled with X's and O's.

- The board has three rows.
- Each row has three columns.
- The board contains only X's and O's - and no other items.


### Release 1. Converting tabular data to a nested array 

```javascript.
let tableData = [
  ["firstName", "lastName", "city", "state"]
  ["Elisabeth", "Gardenar", "Toledo", "OH"],
  ["Jamaal", "Du", "Sylvania", "OH"],
  ["Kathlyn", "Lavoie", "Maumee", "OH"]
]

convertTable(tableData)
=> [
 { "firstName" : "Elisabeth", "lastName" : "Gardenar", "city" : "Toledo", "state" : "OH" }
 { "firstName" : "Jamaal", "lastName" : "Du", "city" : "Sylvania", "state" : "OH" }
 { "firstName" : "Kathlyn", "lastName" : "Lavoie", "city" : "Maumee", "state" : "OH" }
]
```
*Figure 2*. Converting table data into an array of objects.

In this release, you're supposed to convert a nested array into an array of objects. In other words, you have to convert an array consisting of arrays into an array consisting of objects. Let's write the `convertTable` method (see Figure 2).

## Conclusion.

In this task you have learned how to work with arrays. Before we move on, make sure that you have answered all the questions that have arisen in this task.
