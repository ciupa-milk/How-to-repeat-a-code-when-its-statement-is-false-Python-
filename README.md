# How-to-repeat-a-code-when-its-statement-is-false-Python-
If u are a noob like me, then u need this.
x = 5
y = int(input("Num:"))

while True:
    if x == y:
        print("Good")
        break
    else:
        print("Wrong")
        y = int(input("Num"))
        
