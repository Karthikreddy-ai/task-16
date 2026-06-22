
length = float(input("Enter the length of the rectangle: "))
width = float(input("Enter the width of the rectangle: "))

area = length * width
perimeter = 2 * (length + width)

print("Area of rectangle:", area)
print("Perimeter of rectangle:", perimeter)
def compare_numbers(a, b):
    if a > b:
        print(f"{a} is greater than {b}")
    elif a < b:
        print(f"{a} is smaller than {b}")
    else:
        print(f"{a} is equal to {b}")
compare_numbers(10, 20)
compare_numbers(15, 15)
num = int(input("Enter a number: "))

if num >= 10 and num <= 50:
    print("Number is within the range 10–50")
else:
    print("Number is outside the range")


text = input("Enter a word: ")
if text == "Python" or text == "python":
    print("You entered Python!")
else:
    print("Not a match")

x = 10
print("Initial value of x:", x)

x += 5   # x = x + 5
print("After += :", x)

x -= 3   # x = x - 3
print("After -= :", x)

x *= 2   # x = x * 2
print("After *= :", x)

x /= 4   # x = x / 4
print("After /= :", x)

x %= 3   # x = x % 3
print("After %= :", x)

x **= 2  # x = x ** 2
print("After **= :", x)
🆔 Identity & Membership Operators
python

a = [1, 2, 3]
b = a
c = [1, 2, 3]

print("a is b:", a is b)       
print("a is c:", a is c)       
print("a is not c:", a is not c)


numbers = [10, 20, 30, 40]
print("20 in numbers:", 20 in numbers)       
print("50 not in numbers:", 50 not in numbers)  

word = "Python Programming"
print("'Python' in word:", "Python" in word)   
print("'Java' not in word:", "Java" not in word)  
