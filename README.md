# JS_Perfect-number
PYTHON Codes  =>
def perfect_verification(number):
    dividers = [i for i in range(1,number) if number%i==0]
    sum_dividers = 0
    for i in dividers:
        sum_dividers +=i
    if sum_dividers == number: return "It's a perfect number"
    else: return "It's not a perfect number"