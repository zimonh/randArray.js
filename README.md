# randArray.js
Function for making an array filled with random data using an array as input.

# Example

```
const test2 = randArray(['cheeze','panda','table'],200);
console.log(test2);
//=> Array(200) [ "table", "cheeze", "cheeze", "panda", "table", "cheeze", "cheeze", "panda", "panda", "panda", … ]


const NumbersArray = [...Array(512).keys()];
//=> Array(512) [0, 1, 2, 3, … , 511]

const test = randArray(NumbersArray,100);
console.log(test);
//=> Array(100) [ 142, 239, 346, 249, 462, 204, 167, 429, 458, 21, … 
```

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br>
Copyright - ZIMONH 2018
