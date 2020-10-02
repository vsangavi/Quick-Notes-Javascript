### **Array.prototype.reduce()**

Example:

> const array1 = [1, 2, 3, 4];\
> const reducer = (accumulator, currentValue) =>{
> console.log(accumulator)
> console.log("Current",currentValue)
> return (accumulator + currentValue)};\
> console.log(array1.reduce(reducer));\

In this example we use reduce function.\
What does it do?\

1. It has a callback as an argument.
2. That call back functions mainly have accumulator and the current value .
3. Acccumulator stores the result value .
4. Current value has the araay value.\
   In this example initially when we define a callback accumulator will be having the value as 1 {1st element of the array} and the current value will be having the value as 2{2nd value of the array} after that it performs the addition operation and the sum {3} is stored in the accumulator value and now the current value will be 3 {which is the 3rd element of the array}
