def calculate_digit_product(numbe):
    product = 1

    for digit in str(abs(number)):
        product *= int(digit)

    return product


if __name__ == "__main__":
    number = 2345

    print(f"Number: {number}")
    print(f"Digit product: {calculate_digit_product(number)}")
