n=int(input('enter number:'))
ascii_value=97
for i in range(1,n+1):
    for j in range(1,n+1):
        print(chr(ascii_value),end=" ")
        ascii_value+=1
    print("\n")

Output:
enter number:4
a b c d 

e f g h 

i j k l 

m n o p 

>
