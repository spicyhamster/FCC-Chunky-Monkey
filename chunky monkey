//Write a function that splits an array (first argument) into groups the length of size (second argument) and returns them as a two-dimensional array.

function chunkArrayInGroups(arr, size) {
  var myArr = [];
  for(i = 0; i < arr.length; i+=size){
    myArr.push(arr.slice(i, i+size));
  }
  return myArr;
}

chunkArrayInGroups(["a", "b", "c", "d"], 2); //should return [["a", "b"],["c", "d"]]
