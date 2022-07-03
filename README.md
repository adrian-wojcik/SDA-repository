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



# Napisz program, który wyświetli wszystkie liczby naturalne z przedziału 0, 50.

    def funk_1():
        for item in range(0, 50):
            print(item)
        else:
             pass

# Napisz program, który wyświetli wszystkie liczby parzyste z przedziału 0, 100.

    def funk_2():
        for item in range(0, 100):
            if item%2 == 0:
                print(item)
            else:
                pass
            
# Napisz program, który wyświetli na ekranie kwadraty wszystkich liczb całkowitych z przedziału 0, 10.

    def funk_3():
        for item in range(0, 10):
             print(item**2)
        else:
            pass

# Korzystając z pętli, wypisz liczby od -20 do 20. Następnie wypisz:

def funk_4():

    range_1 = range(-20, 21)
    for item in range_1:
         print(item)

# Napisz program, który wyświetli liczby będące wielokrotnością 5 i podzielne przez 7 z przedziału 1500-2700.

    def funk_5():
        for item in range(1500, 2700):
            if item%5 == 0 and item%7 ==0:
                print(item)
            else:
                pass

# Napisz program, który wypisze na ekranie liczby od 0 do 6 z pominięciem 3 i 6. Zrób to w dwóch wersjach: z użyciem instrukcji continue i bez tej instrukcji.

    def funk_6():
        for item in range(0,7):
            if item != 3 and item != 6:
                print(item)
            else:
                pass

# with continue option

    while True:
         for item in range(0,7):
            if item == 3 or item == 6:
                continue
            else:
                print(item)
         break
