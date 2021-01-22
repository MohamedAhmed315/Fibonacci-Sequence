# fibonacci
Fibonacci Number



let fibonacci = function(end){

    let array1 = [];

    array1[0] = 1;
    array1[1] = 1;

    for (let i = 2; i < end; i++){
        array1[i] = array1[i-1] + array1[i-2];
    }
    return array1;
}

console.log("Fibonacci Series = " + fibonacci(12) + ",...");
