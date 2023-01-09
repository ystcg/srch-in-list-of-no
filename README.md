def list_fun (L, item):
    found=False
    for i in range(len(L)):
        if L[i]==item:
            found=True
            print(item, "found at index", i)
            if found == False:
                print(item, "not found in the list")
            else:
                print(item, "found in the list", L.count(item), "times")
List=eval(input("Enter list elements:"))
print("The list is:", List)
ele=int(input("Enter the element to be searched:"))
list_fun(List, ele)
