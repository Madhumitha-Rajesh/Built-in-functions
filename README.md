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
      

