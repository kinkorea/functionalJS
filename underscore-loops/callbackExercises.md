##Callback exercises

1. Use _.each to loop through an array and console.log() all the values. Now use it to console.log() the indices. How would this be different if you were looping through an object?

var array = [1, 2, 3, 4, 5];

array.forEach(function(entry);{
  console.log(entry);
  }


if looping through an object...

var array = {
"arr1": "value1",
"arr2": "value2",
"arr3": "value3",
}

Object.keys(array).forEach(function(key){
  console.log(key);
  });


for (var i in array)



2. Write a function called checkValue that searches an array for a value. It takes an array and a value and returns true if the value exists in the array, otherwise it returns false.

		var helloArr = ['bonjour', 'hello', 'hola'];
		
		var checkValue = function(arr, val) {
		  (for var i=0; i < val.length; i++) {
		    if (val[i] === arr){
		      return true;
		  }
		    return false;
		}
		
		
		
3. Rewrite checkValue using _.each. Make sure that you have underscore.js included where you are running your code.

4. Write a loop that pushes all the values in an object to an array.

		input: {two: 2, four: 4, three: 3, twelve: 12}
		output: [2, 4, 3, 12]
		
		for (var element in input){
		output.push(input[element]);
		}

5. Use _.map to mimic the previous behavior. 

		input: {two: 2, four: 4, three: 3, twelve: 12}
		output: [2, 4, 3, 12]
		
		
6. Use _.filter to return all the even numbers in an array.

		input: [9,8,7,6,5,2]
		output: [8,6,2]
		
		var even = function(num){
		return num % 2 === 0;
		};
		
		var evenArray = Array.filter(even);
		
		
		
