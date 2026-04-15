# Arham-Aryan
def greet(name):
    print(f"Hello, {name}!")

greet("Arham")


def my_function():
    x = 10
    print("Local variable x:", x)

my_function()


y = 20

def access_global():
    print("Accessing global variable y:", y)

access_global()


def modify_global():
    global y
    y = 30

modify_global()
print("Modified global variable y:", y)
