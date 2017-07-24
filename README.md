# primelib

Welcome to the primelib package (Version 1.0.0)
***********************************************

Introduction: What this package is about
=========================================================

The primelib package is a python package that helps in using and implementing prime numbers in Python 3.X.
This is a very simple package and is generally recommended for larger projects where prime numbers play an important part


Usage
=========================================================

The package contains the following functions:

    1. isprime(n): Checks if the number 'n' is prime or not. Returns True if prime and False if composite
    2. find_primes(start, stop): Returns a list of prime numbers in the range [start, stop], including the end values
    3. rand_prime(start, stop): Generate a randome prime number belonging to the range [start, stop], including the end values
    4. inter_primes(start, stop, [, interval]): Returns a list, of tuples of prime numbers, that are separated by 'interval'.
       In case the parameter 'interval' is not specified, this is same as 2. Useful for printing twin primes (primes that
       are 2 units apart), sexy primes (primes that are 6 units apart, and yes they are called 'sexy' primes, etc.)
