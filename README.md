#list methods

l=[12,27,56,87,16,12]
print("The original list:",l)

l.append(25)
print("List after appending 25:",l)

l.insert(1,7)
print("List after inserting 7 at index 1:",l)

l.remove(56)
print("List after removing 56:",l)

l.pop(3)
print("List after popping 87:",l)

l.extend([4,5])
print("List after extending [4,5]:",l)

print("Number of 12s in the list:",l.count(12))

print("Index of 16:",l.index(16))

l.sort()
print("Sorted list:",l)

l.reverse()
print("Reversed list:",l)

cp=l.copy()
print("Copied list:",cp)

print("Length of list:",len(l))

print("Maximum element in the list:",max(l))
print("Minimum element in the list:",min(l))
print("Sum of list:",sum(l))

l.clear()
print("List after clear:",l)

Output:

The original list: [12, 27, 56, 87, 16, 12]
List after appending 25: [12, 27, 56, 87, 16, 12, 25]
List after inserting 7 at index 1: [12, 7, 27, 56, 87, 16, 12, 25]
List after removing 56: [12, 7, 27, 87, 16, 12, 25]
List after popping 87: [12, 7, 27, 16, 12, 25]
List after extending [4,5]: [12, 7, 27, 16, 12, 25, 4, 5]
Number of 12s in the list: 2
Index of 16: 3
Sorted list: [4, 5, 7, 12, 12, 16, 25, 27]
Reversed list: [27, 25, 16, 12, 12, 7, 5, 4]
Copied list: [27, 25, 16, 12, 12, 7, 5, 4]
Length of list: 8
Maximum element in the list: 27
Minimum element in the list: 4
Sum of list: 108
List after clear: []


