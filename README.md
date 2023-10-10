# string_replace_letter.py
#replacing with star 
#program is replacing with by this symbol"*" in vowels

#requirements
#string
#replace charecter (special or any letter)


def replacevowel(st):
    newstr= ' '
    for charecter in st:
        if charecter in ("aeiouAEIOU"):
            newstr+="*"
        else:
            newstr+=charecter
    return newstr
#function ends here
st=input("enter a string:")
#function calling here
replacevowel(st)
print("original string is:", st)
print("the modified stering is:",replacevowel(st))

#input and output
original string is: hai rajesh how are you ,where are you studying
the modified stering is:  h** r*j*sh h*w *r* y** ,wh*r* *r* y** st*dy*ng



