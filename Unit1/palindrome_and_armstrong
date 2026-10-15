import Foundation

let number = 153

// Palindrome check
var originalForPalindrome = abs(number)
var reversedNumber = 0
var temporaryNumber = originalForPalindrome

while temporaryNumber > 0 {
    let digit = temporaryNumber % 10
    reversedNumber = reversedNumber * 10 + digit
    temporaryNumber /= 10
}

if originalForPalindrome == reversedNumber {
    print("\(number) is a palindrome")
} else {
    print("\(number) is not a palindrome")
}

// Armstrong number check
let digits = String(abs(number)).count
var remainingNumber = abs(number)
var armstrongSum = 0

if remainingNumber == 0 {
    armstrongSum = 0
} else {
    while remainingNumber > 0 {
        let digit = remainingNumber % 10
        armstrongSum += Int(pow(Double(digit), Double(digits)))
        remainingNumber /= 10
    }
}

if armstrongSum == abs(number) {
    print("\(number) is an Armstrong number")
} else {
    print("\(number) is not an Armstrong number")
}
