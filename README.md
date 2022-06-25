# PYTHON PROJE

- FLATTEN

def flatten(a):
    new_a = []
    for b in a:
        if type(b) != type([]):
            new_a.append(b)
        else:
            new_a.extend(flatten(b))
    return new_a

- REVERSE 

a =[[1, 2], [3, 4], [5, 6, 7]]
a=a[::-1]

for i in range(len(a)):
    (a[i])=(a[i])[::-1]
print(a)