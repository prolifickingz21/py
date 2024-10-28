total = 0
index = 1
while index  <= 10:
    if index % 2 == 0:
        index += 1
        continue
    total += index
    index += 1

roster = ['mainoo', 'jon', 'car', 'more']
for name in roster:
    print(name)
for i in range(3):
    print(roster[1])
