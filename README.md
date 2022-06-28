# Kalkulator standardowy:

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
