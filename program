def add_random_list (list=[]):
    import random
    for i in range (0, random.randint(0,20)):
        list.append(random.randint(0,100))
    print("Ваш список:", list, sep="\n")
    print("\n")
    return list

def sort (list, i=0):
    while i<len(list)-1:
        k=list[i]
        list[i]=list[i+1]
        list[i+1]=k
        i+=2
    print("Отсортированный список:", list, sep="\n")
    return list
list= add_random_list ()
sort(list)
