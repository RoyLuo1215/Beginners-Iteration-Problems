1
password = "123"
attempts = 3
while attempts > 0:
    user_input = input("Enter Password: ")
    if user_input == password:
        print("Correct Password")
    else:
        attempts -= 1
        if attempts == 0:
            print("Locked")


2
def name_loop():
    num = int(input("Enter a number: "))
    name = input("Enter your name: ")

    for _ in range(num):
        print(name)
name_loop()

3
def print_multiplication_table():
    while True:
        try:
            num = int(input("Enter a positive integer: "))
            if num <= 0:
                print("Not a positive integer.")
            else:
                break
        except ValueError:
            print("Invalid input. Please enter a positive integer.")

    print("Multiplication table for", num)
    for i in range(1, 11):
        print(num, "x", i, "=", num * i)


print_multiplication_table()

4
def is_prime(number):
    if number <= 1:
        return False
    elif number <= 3:
        return True
    elif number % 2 == 0 or number % 3 == 0:
        return False
    i = 5
    while i * i <= number:
        if number % i == 0 or number % (i + 2) == 0:
            return False
        i += 6
    return True

def main():
    try:
        num = int(input("Enter an integer: "))
        if is_prime(num):
            print(num, "is a prime number.")
        else:
            print(num, "is not a prime number.")
    except ValueError:
        print("Invalid input. Please enter an integer.")
main()

5
def fizzbuzz_game():
    for i in range(1, 101):
        if i % 3 == 0 and i % 5 == 0:
            print("FizzBuzz")
        elif i % 3 == 0:
            print("Fizz")
        elif i % 5 == 0:
            print("Buzz")
        else:
            print(i)
fizzbuzz_game()
