# combines-two-lists-by-alternatingly-taking-elements



var arr1=["a","b","c"];
var arr2=[1,2,3];
function newArray(arr1,arr2) {
var arr3=[];
for(i=0;i<arr1.length;i++) {

arr3.push(arr1[i]);
arr3.push(arr2[i]);
          }
return arr3;

          }
console.log(newArray(arr1,arr2));


Output:[a,1,b,2,c,3]
