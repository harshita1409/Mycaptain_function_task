import operator
def most_frequent(name):
    dict = {} 

    for i  in name :

        keys = dict.keys()

        if i not in keys :
            dict[i] = 1
        else:
            dict[i] += 1 

    return sorted(dict.items(),key = operator.itemgetter(1),reverse = True) 

a = input("Please enter a string: ")
print(most_frequent(a))
