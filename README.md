# Icons
## How to Use
When creating a symbol, you will be asked to input values for the following keys:
* auto (true or false): If true, a symbol containing the name in the “symbol” key will be used. If false, the exact name of the symbol in the “symbol” key will be used
* symbol: the name of the symbol to be used
* icon color: the hex code for the color of the icon (if it has no value or does not have 6 letters, it will default to #ffffff)
* bg color: the hex code for the color of the background (defaults to #181818)
* icon scale: can be any number above 0, but if it is above 1 the icon might be cut off. 1 is 100%, 5 is 50% and so on

## Fastest Way
The quickest way to create a lot of Symbols would be to create a dictionary with an array at the key “list” that contains dictionaries formatted in the same way as explained above
