# prosty-kalkulator

def main():
    odp = True
    while odp:
        print("Podaj w oddzielnych wierszach liczbę, operację matematyczną: +,-,*,/,%, a następnie kolejną liczbę:")
        numberOne = input()
        operation = input()
        numberTwo = input()
        if operation == "+":
            print("Twój wynik to: ", (int)(numberOne) + (int)(numberTwo))
        elif operation == "-":
            print("Twój wynik to: ", (int)(numberOne) - (int)(numberTwo))
        elif operation == "*":
            print("Twój wynik to: ", (int)(numberOne) * (int)(numberTwo))
        elif operation == "/":
            print("Twój wynik to: ", (int)(numberOne) / (int)(numberTwo))
        elif operation == "%":
            print("Twój wynik to: ", (int)(numberOne) % (int)(numberTwo))
        else:
            print("sporóbuj jeszcze raz")

        odp = input("Chcesz wykonać kolejne działanie? Wpisz literę t lub n ") == "t"
if __name__ == "__main__":
    main()

