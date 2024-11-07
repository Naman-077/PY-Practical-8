# PY-Practical-8
def cubes():
    number = [1, 2, 3, 4, 5, 6, "seven"]
    even_cubes = [i**3 for i in number if isinstance(i, int) and i % 2 == 0]
    print(even_cubes)

cubes()



'''output
[8, 64, 216]
'''
