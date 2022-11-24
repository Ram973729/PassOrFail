# PassOrFail
sno=int(input('Enter sno:'))
name=input('Enter name:')
group=input('Enter group:')
s1=int(input('Enter maths marks:'))
s2=int(input('Enter physics marks:'))
s3=int(input('Enter chemistry marks:'))
print(sno),print(name),print(group)
if (s1>=35)and(s2>=35)and(s3>=35):
    print('Pass')
else:
    print('Fail')
