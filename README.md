# What is a Prime Number?
A prime number has only two factors: one and itself. A factor divides the number perfectly leaving no remainder behind. 

In mathematical terms: number % factor = 0 

# Finding The kth Prime Number
The method kthPrime searches for the 1st - 30 000th prime number in less than one minute from the infinite sequence of prime numbers (Primes.java goes up to 50 000).

## Sieve of Eratosthenes Algorithm

- Start a the prime number 2 and eliminate all other multiples of 2, thus eliminating composite numbers

- Move on to 3 and eliminate all other multiples of 3

- Move on to 5 and eliminate all other multiples of 5 etc... 

- After the list of primes is created, the kth prime is obtained from the list

![Sieve_of_Eratosthenes_animation](https://user-images.githubusercontent.com/59797227/105047827-d26d9f00-5a38-11eb-8242-3ca2cbfda342.gif)

# Prime Factors of an Integer Algorithm
The returned list of the method needs to contain all the prime factors in ascending sorted order. For example, if n = 220, [2, 2, 5, 11] is returned.

- If the integer is even, list all occurences of 2 that divide the integer. The integer n is repeatedly divided by 2 and each successful division is listed.

- If the integer is odd, n is repeatedly divided by 3 and each successful division is listed.

- If the number is not divisible by 3 move on to the next odd prime number until the square root of the integer n is reached.

- When the integer cannot be divided anymore and a prime number is left, list that prime number.

![prime-factorization-calculator](https://user-images.githubusercontent.com/59797227/105271225-21b0ee00-5b65-11eb-83e0-d6bf88bb5f00.gif)

Kudos to the authors of the gifs!

https://commons.wikimedia.org/wiki/File:Animation_Sieve_of_Eratosth.gif

https://www.dadsworksheets.com/prime-factorization-calculator.html
