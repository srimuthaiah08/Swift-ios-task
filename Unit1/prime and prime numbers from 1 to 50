import Foundation

let number = 29
var isPrime = number >= 2

if number >= 2 {
    var divisor = 2
    while divisor * divisor <= number {
        if number % divisor == 0 {
            isPrime = false
            break
        }
        divisor += 1
    }
} else {
    isPrime = false
}

if isPrime {
    print("\(number) is prime")
} else {
    print("\(number) is not prime")
}

print("Prime numbers between 1 and 50:")
for candidate in 2...50 {
    var candidateIsPrime = true
    var divisor = 2

    while divisor * divisor <= candidate {
        if candidate % divisor == 0 {
            candidateIsPrime = false
            break
        }
        divisor += 1
    }

    if candidateIsPrime {
        print(candidate, terminator: " ")
    }
}
print()
