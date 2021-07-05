# most_frequent-letter-in-decreasing-order
S= input("enter a string")
def most_frequent(string):
    d = dict()
    for i in string:
        if i not in d:
            d[i] = 1
        else:
            d[i] += 1
    return d

print (most_frequent(S))
