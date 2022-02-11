Sno=int(input("enter sno:"))
Sname=(input("enter sname:"))
s1=int(input("enter maths marks:"))
s2=int(input("enter physics marks:"))
s3=int(input("enter computer marks:"))
s4=int(input("enter english marks:"))
s5=int(input("enter telugu marks:"))
s6=int(input("enter crt marks:"))
total=s1+s2+s3+s4+s5+s6
avg=total/6
if avg>=91:
    print("o-grade")
elif avg>=81:
    print("a-grade")
elif avg>=71:
    print("b-grade")
elif avg>=61:
    print("c-grade")
elif avg>=51:
    print("d-grade")
elif avg>=41:
    print("pass")
elif avg<=40:
    print("fail")
    
    
    
    outpu:
    enter sno:27
    enter sname:sowjanya
    enter maths marks :95
    enter physics marks:76
    enter computer marks :91
    enter english marks :75 
    enter telugu marks :80 
    enter crt marks :87
    a-grade
