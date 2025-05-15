//Initialize the array that will hold the primes
var primeArray = [];
/*Write a function that checks for primeness and
pushes those values to the array*/
function PrimeCheck(candidate){
  isPrime = true;
  for(var i = 2; i < candidate && isPrime; i++){
    if(candidate%i === 0){
      isPrime = false;
    } else {
      isPrime = true;
    }
  }
  if(isPrime){
    primeArray.push(candidate);
  }
  return primeArray;
}
/*Write the code that runs the above until the
length of the array equals the number of primes
desired*/

var numPrimes = prompt("How many primes?");

//Display the finished array of primes

//for loop starting at 2 as that is the lowest prime number keep going until the array is as long as we requested
for (var i = 2; primeArray.length < numPrimes; i++) {   
    PrimeCheck(i); //
}
console.log(primeArray);