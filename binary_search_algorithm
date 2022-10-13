list_of_integers = [9,11,19,24,30,44,66,73,80]
target = int(input("what number:"))

def bin_search(list, targ):
    low = 0
    high = len(list)-1
    while low<=high:
        mid = (low+high)//2
        if list[mid] == targ:
            return f"{targ} can be found at index {mid}"
        elif list[mid]<targ:
            low = mid+1
        else:
            high = mid-1
    return f"{False}, cannot be found"

print(bin_search(list_of_integers,target))
