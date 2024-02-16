# GradeCalc
# Name: Paola N.
# Date: October 28, 2020

print("Welcome to GradesCALC =^U w U^=")
print("""""")
print("""1. Final Grade""")
print("""2. Exit / Quit""")
print("""""")
ans = True
ans = input("What do you want to calculate today love? ")
print("""""")
if ans == "1":
    print("# Final-GradeCALC #")
    print("""""")

# input:
C = float(input('Enter your current grade in the class: '))
W = float(input('Enter the weight of the final exam: '))
G = float(input('Enter your desired grade for the class: '))

# constants:
N = 100

# processing:
W = W / N
F = (G - ((1 - W) * C)) / W

# output:
print("You need " + str(F) + "%" + " to get " + str(G) + "% in the class.")
print("""""")
if ans == "2":
    print("Goodbye Love, <3")
    exit()

print("""1. YES""")
print("""2. NO""")
ans2 = True
ans2 = input("Do you still want to calculate? ")
print("""""")

if ans2 == "1":
    print("""1. Final-GradeCALC""")
    print("""2. Exit / Quit""")

else:
    exit()

ans3 = True
ans3 = input("What do you want to calculate? ")
print("""""")

if ans3 == "1":
    print("# Final-GradeCALC #")
    print("""""")

# input:
C = float(input('Enter your current grade in the class: '))
W = float(input('Enter the weight of the final exam: '))
G = float(input('Enter your desired grade for the class: '))

# constants:
N = 100

# processing:
W = W / N
F = (G - ((1 - W) * C)) / W

# output:
print("You need " + str(F) + "%" + " to get " + str(G) + "% in the class.")
print("""""")





