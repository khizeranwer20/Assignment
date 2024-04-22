# Assignment
Question: 1
function reverseArray(arr) 
{
    let reverseArray = [];
    for (let i = arr.length - 1; i >= 0; i--) 
    {
        reverseArray.push(arr[i]);
    }
    return reverseArray;
}

const inputArray = [1, 2, 3];
console.log('Input:', inputArray);
console.log('Reversed:', reverseArray(inputArray));

Question: 2
var firstInput=[1,2,3];
var secondInput=[4,5,6];
function combine ()
{
    let X=  [firstInput + secondInput] ;
    return X;
}
console.log(combine());

Question: 3
function onearray(lens, k){
    for(let i=0;i<k;i++)
    {
        let rotate=lens.pop();
        lens.unshift(rotate);
    }
    return lens;
  }
  const InputArray=[1,2,3,4,5,6,7];
  const k=3;
  console.log("Rotated:["+ onearray(InputArray,k)+"]");

Question: 4
function print(rows)
{

for(let i=1;i<=rows;i++)
{
    let pattern= "";
 for(let j=rows-i;j>0;j--)
 {
    pattern += ".";
 }
 for(let k=0;k<i;k++){
    pattern +=i;
 }
 console.log(pattern);
}

 
}
print(5);
