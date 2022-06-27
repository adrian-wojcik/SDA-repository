#Kalkulator standardowy:

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
    
    
# Kalkulator BMI

def kalkulator_BMI():

        a = int(input("Wprowadź swoją wagę (w kilogramach): \n"))
        b = int(input("Wprowadź swój wzrost (w CENTYMETRACH np.: 180): \n"))
        b = b / 100
        b = b ** 2
        while a > 0 and b > 0:
            if a > 0 and b > 0:
                print(f"Twoje BMI wynosi: {round(a / b, 2)}")
            if a / b <= 18.5:
                print("Masz niedowagę")
            elif a / b >= 18.5 and a / b <= 24.9:
                print("Masz optymalną wagę")
            elif a / b >= 25 and a / b <= 29.9:
                print("Masz nadwagę")
            elif a / b >= 30 and a / b <= 34.9:
                print("Jesteś otyły")
            elif a / b >= 35:
                print("Zacznij Biegać!!!")
            else:
                continue
        breakpoint(print(f"Wprowadzone parametry są nieprawidłowe!"))
