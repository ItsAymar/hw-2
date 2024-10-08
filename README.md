# 4-6
for number in range(1, 21, 2):
    print(number)

# 4-7
#multiples_of_3 = {}
#for number in range(3, 31, 3):
#    multiples_of_3.append(number)
#for multiple in multiples_of_3:
#    print(multiple)

multiples_of_3 = []


for number in range(3, 31, 3):
    multiples_of_3.append(number)  


for multiple in multiples_of_3:
    print(multiple)

#4-8
cubes = []

for i in range(1, 11):
    cubes.append(i ** 3)  

for cube in cubes:
    print(cube)

#4-9
cubes = [i ** 3 for i in range(1, 11)]

for cube in cubes:
    print(cube)

#fibonacci sequence 

a = 0
print(a)
b = 1
print(b)

for i in range(18):
    c = a + b
    print(c)
    a = b
    b = c

x = 400/ 3
print(x)
x = 3
y = 2
z = 4
answer = (x + y) ** (z + y)
print(answer)

verb = "love"
verb = "write"

if verb== "hate":
    verb = "love"
elif verb != "hate":
    print(f"I {verb} Python.")
else:
    print

for i in range(20):
    print(i)

def do_math(x, y):
	return x + y

sum = do_math(2,3)
print(sum)
# change so that sum can accept three arguments:
sum = do_math(2,3,4)
print(sum)

def do_math(x, y, z):
	answer = x + y + z
    print(answer)
