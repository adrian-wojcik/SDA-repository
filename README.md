# Standard Calculator:

def kalk_standardowy():

    a = int(input("Wprowadz pierwsza liczbe: \n"))
    b = str(input("Wprowadz znka wykonywanej operacji(+, -, *, /, %) \n"))
    c = int(input("Wprowadz druga liczbe: \n"))

    if b == "+":
        print(f"Wynik twojego działania: {a + c}")
    elif b == "-":
        print(f"Wynik twojego działania: {a - c}")
    elif b == "*":
        print(f"Wynik twojego działania: {a * c}")
    elif b == "/":
        print(f"Wynik twojego działania: {a / c}")
    elif b == "%":
        print(f"Wynik twojego działania:{a % c}")
    else:
        print(f"Znak {b} nie jest obługiwany")

    exit(print("Miłego dnia :)"))
    
# Standard Calculator_2:

    def funki_sum(x, b, y):
    if b == "+":
        print(x + y)
    else:
        pass

    def funki_subtraction(x, b, y):
    if b == "-":
        print(x - y)
    else:
        pass

    def funki_multiply(x, b, y):
    if b == "*":
        print(x * y)
    else:
        pass

    def funki_divided(x, b, y):
    if b == "/":
        print(x / y)
    else:
        pass

    def funki_modulo(x, b, y):
    if b == "%":
        print(x % y)
    else:
        pass

    def funki_kalkulator():


    x = float(input("Wprowadź pierwszą liczbę \n"))
    b = input("Wprowadź znak wykonywanej operacji \n")
    y = float(input("Wprowadź drugą liczbę \n"))

    if b == "+" or "-" or "*" or "/" or "%":
        if b == "+":
            return funki_sum(x, b, y), print("Miłego dnia! :D \n")
        elif b == "-":
            return funki_subtraction(x, b, y), print("Miłego dnia! :D \n")
        elif b == "*":
            return funki_multiply(x, b, y), print("Miłego dnia! :D \n")
        elif b == "/":
            return funki_divided(x, b, y), print("Miłego dnia! :D \n")
        elif b == "%":
            return funki_modulo(x, b, y), print("Miłego dnia! :D \n")
        else:
            print("Nieznana funkcja - dostępne funkcje to: '+' '-' '*' '/' '%'")
    print("Miłego dnia! :D")

    

# Kalkulator BMI:
    
    def kalkulator_BMI():

    while True:
        a = int(input("Wprowadź swoją wagę (w kilogramach): \n"))
        b = int(input("Wprowadź swój wzrost (w CENTYMETRACH np.: 180): \n"))
        b = b / 100
        x = b ** 2

        if a > 0 and b > 0:
            print(f"Twoje BMI wynosi: {round(a / b, 2)}")
            if a / x > 0 and a / x <= 18.5:
                print("Masz niedowagę")
            elif a / x >= 18.5 and a / x <= 24.9:
                print("Masz optymalną wagę")
            elif a / x >= 25 and a / x <= 29.9:
                print("Masz nadwagę")
            elif a / x >= 30 and a / x <= 34.9:
                print("Jesteś otyły")
            elif a / x >= 35:
                print("Masz poważną nadwagę")
            else:
                break
        else:
            print("Wprowadzone dane są nieprawidłowe")
            continue
    exit()



# Write a program that will display all natural numbers between 0 and 50.

    def funk_1():
        for item in range(0, 50):
            print(item)
        else:
             pass

# Write a program that will display all even numbers between 0, 100.

    def funk_2():
        for item in range(0, 100):
            if item%2 == 0:
                print(item)
            else:
                pass
# Write a program that will display on the screen the squares of all integers in the range 0, 10.
def funk_3():

    for item in range(0, 10):
         print(item**2)
    else:
        pass

# Using a loop, write numbers from -20 to 20. Then write:

    def funk_4():

    #The first 6 numbers
    for item in range(-20, 21)[0:6]:
        print(item)

    #The last 6 numbers
    for item in range(-20, 21)[35:41]:
        print(item)

    # All even numbers
    for item in range(-20, 21):
        if item%2 == 0:
            print(item)

    # All numbers except 5
    for item in range(-20, 21):
        if item != 5:
            print(item)

    # All numbers up to and including 7
    for item in range(-20, 21)[0:28]:
        print(item)

    # All numbers divisible by 3
    for item in range(-20, 21):
        if item%3 == 0:
            print(item)
            
    # Sum of all numbers
    x = sum(range(-20, 21))
    print(x)

    # All the numbers and their powers
    for item in range(-20, 21):
        print(item,">>potęga>>" ,item*item)

    # All numbers and their values modulo 10
    for item in range(-20, 21):
        print(item, ">>modulo 10>>", item%10)


# Write a program that will display numbers that are multiples of 5 and divisible by 7 between 1500-2700.

    def funk_5():
        for item in range(1500, 2700):
            if item%5 == 0 and item%7 ==0:
                print(item)
            else:
                pass

# Write a program that prints the numbers 0 through 6 to the screen, skipping 3 and 6.
# Do this in two versions: with the continue statement and without the continue statement.

    def funk_6():
        for item in range(0,7):
            if item != 3 and item != 6:
                print(item)
            else:
                pass

    # Z opcja continue
    while True:
         for item in range(0,7):
            if item == 3 or item == 6:
                continue
            else:
                print(item)
         break
