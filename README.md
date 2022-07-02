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
