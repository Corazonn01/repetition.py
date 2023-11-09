# repetition.py
here you can see how to repeat each character from the list 

# string repetition 
new_list2 = ["abc"]
for k in new_list2:
    new = ''
    for u in k:
        new += u*2
    print(new)

# int repetition 
new_list = [1, 8, 9]
for i in new_list:
    new_list = []
    for char in str(i):
        new_list += char *2
    print(new_list)

# repetition for fun 
new_list2 = ["My name is Elina, hello", 'i am 22 years old']
for k in new_list2:
    new = ''
    for u in k:
        new += u*2
        print(new)
