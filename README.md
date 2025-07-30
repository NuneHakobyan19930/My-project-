a = [2, 5, 4, 3, 6, 14, 3, 2, 37]
i = 0
t = 7
found = False

while i <= len(a) - 1:
    if a[i] > t:
        print(f"Number {a[i]} at index {i} is greater than {t}.")
        found = True
        break
    i += 1

if not found:
    print("There is no number greater than 7.")
