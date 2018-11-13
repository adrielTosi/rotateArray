# rotateArray
Takes an array and a number, and moves each element however many spaces the number is to the right and log in the console


function rotate (arr, num){ 
    let length = arr.length;
    let newArray = [];

    for(i = length -1; i >= length - num; i--){
        newArray.unshift(arr[i])
    }
    for(i = 0; i < length - num; i++){
        newArray[i+num] = arr[i]
    }
return console.log(newArray)
}
